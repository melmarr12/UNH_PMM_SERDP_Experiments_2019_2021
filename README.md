# UNH_PMM_SERDP_Experiments_2019_2021
This project contains the data collected by the University of New Hampshire (UNH) Coastal Processes Lab for three field experiments focusing on investigating munition mobility in nearshore/surfzone regions. The first experiment took place on May 17 2019, the second experiment took place on February 1-2 2021, and the last experiment to place on October 26-27 2021. The data was collected at Wallis Sands Beach in Rye, New Hampshire. 

The main instrument utilized was the Pressure Mapped Munition (PMM), which is a fully autonomous cylindrical surrogate munition that can resolve the pressure field on its surface. The PMM is constructed from a 229 mm long section of 304 stainless steel pipe with a 140 mm outside diameter and 12.7 mm wall thickness. To make autonomous measurements of surface pressure and relative position, the PMM houses 16 high resolution TE Connectivity MS5837-02BA absolute pressure sensors and a Lord MicroStrain 3DM®-GX5-25 inertial measurement unit (IMU). 

For the May experiment, a Nortek Vector was deployed along with the PMM. The Nortek Vector is an Acoustic Doppler Velocimeter (ADV) which collects high-resolution, single-point, 3-dimensional velocity data (Nortek, 2022b). For this experiment the ADV transducer was about 30 cm above the sediment bed while the ADV pressure sensor was about 50 cm above the sediment bed. The Nortek Vector was not deployed for the Feburary and October experiments.

For the February and October experiments, another instrument, the Pressure Stick (PS), was deployed with the PMM. The Pressure Stick is a fully autonomous pressure-profiling instrument. The PS contains eight micro-controlled, time-synced TE Connectivity MS5837-02BA absolute pressure and temperature sensors distributed along a 70 cm distance to measure pressure throughout the water column and into the sediment bed. The Pressure Stick allows for a quantification of intermittent bed instability (momentary liquefaction) and its potential role in munition mobility. More information about the PS can be found in Marry & Foster (2024).

Global Positioning System (GPS) surveys of the beach profile were also completed on February 2, 2021 (at the end of the experiment) and October 26, 2021 (at the beginning of the experiment), and the survey data is also included in this project. Data of the offshore wave conditions as measured by the [Jeffrey's Ledge waverider buoy (station 44098) from the National Data Buoy Center (NDBC)](https://www.ndbc.noaa.gov/station_page.php?station=44098) for all three experiments are given here as well.

This effort was supported by Strategic Environmental Research and Development Program (SERDP, Project Number 17 MR-2731). These datasets are presented in the final report for Project Number 17 MR-2731.

## Dataset files
A description of each data file is given below:

### Pressure Mapped Munition (PMM) Data
1. PMM_20190517.txt
2. IMU_20190517.txt
3. PMM_20210202.txt
4. IMU_20210202.txt
5. PMM_20211026.txt
4. IMU_20211026.txt

### Nortek Vector Data
1. Vector_20190517.txt
     This file contains the Nortek Vector data from the experiment on May 17 2019.
     - Vec_time = time of Vector samples
     - Vpress = pressure in mbar
     - Vpress_smooth = smoothed pressure in mbar
     - Vu = cross-shore velocity in m/s
     - Vv = along-shore velocity in m/s
     - Vw = vertical velocity in m/s

### Pressure Stick (PS) Data
1. PS_20210202.txt

    This file contains the raw data from the Pressure Stick for the February experiment

1. Folder UNH_PSdataS21_Raw

    This folder contains the raw data from the Pressure Stick for the full deployment time (September 10th 2021 22:55:00 - September 12th 7:15:00).
    - UNH_PSdataS21_P.txt = raw pressure (mbar, [2056516x8] vector) 
    - UNH_PSdataS21_dt.txt = datetime ([2056516x1] vector)
    - UNH_PSdataS21_dn.txt = serial datenumber ([2056516x1] vector)
    - UNH_PSdataS21_T.txt = temperature (deg C, [2056516x8] vector)
    - UNH_PSdataS21_Pd.txt = pressure head (m, [2056516x8] vector)
    - UNH_PSdataS21_z.txt = sensor elevations (m, [1x8] vector, negative values in the sediment bed, sensor 1 is the top sensor closest to the circuitry/top of the instrument)

### GPS Data
1. UNH_GPS_WS_20210202.txt (.pos)

    This file contains data from a GPS survey taken on February 2nd 2021 as the post-deployment survey for the February experiment. 
    - GPST = time stamp of the survey sample 
    - latitude = latitude in degrees
    - longitude = longitude in degrees
    - height = elevation height, relative to WGS84/ellipsoidal in meters
    - Q = quality of the data point. Q = 1 is a 'good' data point, Q = 2 is an 'okay' data point, and Q > 2 are 'bad' data points. 
    - ns = Number of satellites
    
2. UNH_GPS_WS_20211026.txt (.pos)

    This file contains data from a GPS survey taken on October 26th 2021 as the pre-deployment survey for the October experiment. 
    - GPST = time stamp of the survey sample 
    - latitude = latitude in degrees
    - longitude = longitude in degrees
    - height = elevation height, relative to WGS84/ellipsoidal in meters
    - Q = quality of the data point. Q = 1 is a 'good' data point, Q = 2 is an 'okay' data point, and Q > 2 are 'bad' data points. 
    - ns = Number of satellites

### Waverider Buoy (NDBC station 44098) Data
1. NDBC_44098_JeffreysLedgeBuoy_May2019.txt

    This file contains offshore wave data from [Jeffrey's Ledge waverider buoy (station 44098) from the National Data Buoy Center (NDBC)](https://www.ndbc.noaa.gov/station_page.php?station=44098) throughout the May 2019 experiment (May 17th 2019 00:08:00 - May 18th 2019 12:38:00). Please see [Description of Measurements](https://www.ndbc.noaa.gov/measdes.shtml) for a discussion of each of the variables in this file.

2. NDBC_44098_JeffreysLedgeBuoy_February2021.txt

    This file contains offshore wave data from [Jeffrey's Ledge waverider buoy (station 44098) from the National Data Buoy Center (NDBC)](https://www.ndbc.noaa.gov/station_page.php?station=44098) throughout the February 2021 experiment (February 1st 2021 01:26:00 - Feburary 2nd 2021 09:56:00). Please see [Description of Measurements](https://www.ndbc.noaa.gov/measdes.shtml) for a discussion of each of the variables in this file.

3. NDBC_44098_JeffreysLedgeBuoy_October2021.txt

    This file contains offshore wave data from [Jeffrey's Ledge waverider buoy (station 44098) from the National Data Buoy Center (NDBC)](https://www.ndbc.noaa.gov/station_page.php?station=44098) throughout the October 2021 experiment (October 26th 2021 00:26:00 - October 27th 2021 23:56:00). Please see [Description of Measurements](https://www.ndbc.noaa.gov/measdes.shtml) for a discussion of each of the variables in this file.
