# UNH_PMM_SERDP_Experiments_2019_2021
This project contains the data collected by the University of New Hampshire (UNH) Coastal Processes Lab for three field experiments focusing on investigating munition mobility in nearshore/surfzone regions. The first experiment took place on May 17 2019, the second experiment took place on February 1-2 2021, and the last experiment to place on October 26-27 2021. The data was collected at Wallis Sands Beach in Rye, New Hampshire. 

The main instrument utilized was the Pressure Mapped Munition (PMM), which is a fully autonomous cylindrical surrogate munition that can resolve the pressure field on its surface. The PMM is constructed from a 229 mm long section of 304 stainless steel pipe with a 140 mm outside diameter and 12.7 mm wall thickness. To make autonomous measurements of surface pressure and relative position, the PMM houses 16 high resolution TE Connectivity MS5837-02BA absolute pressure sensors and a Lord MicroStrain 3DM®-GX5-25 inertial measurement unit (IMU). There are two rings of pressure sensors around the cylinder. Pressure sensors 1-8 are in ring 1 and pressure sensors 9-16 are in ring 2. Each ring is 6.35 cm from the ends of the cylinder and the rings are 15.24 cm apart. The radial spacing between sensors around each ring is 45°, which minimizes the arc length and height difference between sensors while maintaining axial pairs of sensors. This orientation allows for sensor redundancy in the case of sensor failure and allows for error correction if faulty values from one of the sensors is suspected. When the PMM is lying flat the vertical displacement between the topmost and bottommost sensor is 129 - 140 mm depending on the orientation of the instrument. 

For the May experiment, a Nortek Vector was deployed along with the PMM. The Nortek Vector is an Acoustic Doppler Velocimeter (ADV) which collects high-resolution, single-point, 3-dimensional velocity data (Nortek, 2022b). For this experiment the ADV transducer was about 30 cm above the sediment bed while the ADV pressure sensor was about 50 cm above the sediment bed. The Nortek Vector was not deployed for the Feburary and October experiments.

For the February and October experiments, another instrument, the Pressure Stick (PS), was deployed with the PMM. The Pressure Stick is a fully autonomous pressure-profiling instrument. The PS contains eight micro-controlled, time-synced TE Connectivity MS5837-02BA absolute pressure and temperature sensors distributed along a 70 cm distance to measure pressure throughout the water column and into the sediment bed. The Pressure Stick allows for a quantification of intermittent bed instability (momentary liquefaction) and its potential role in munition mobility. More information about the PS can be found in Marry & Foster (2024).

Global Positioning System (GPS) surveys of the beach profile were also completed on February 2, 2021 (at the end of the experiment) and October 26, 2021 (at the beginning of the experiment), and the survey data is also included in this project. Data of the offshore wave conditions as measured by the [Jeffrey's Ledge waverider buoy (station 44098) from the National Data Buoy Center (NDBC)](https://www.ndbc.noaa.gov/station_page.php?station=44098) for all three experiments are given here as well.

This effort was supported by Strategic Environmental Research and Development Program (SERDP, Project Number 17 MR-2731). These datasets are presented in the final report for Project Number 17 MR-2731.

## Dataset files
A description of each data file is given below:

### Pressure Mapped Munition (PMM) Data
1. PMM_20190517.txt
     This file contains the raw data from the PMM for the experiment on May 17, 2019
     - Date = date of sample
     - Time = time of sample
     - P1 = pressure from sensor 1 in mbar
     - P2 = pressure from sensor 2 in mbar
     - P3 = pressure from sensor 3 in mbar
     - P4 = pressure from sensor 4 in mbar
     - P5 = pressure from sensor 5 in mbar
     - P6 = pressure from sensor 6 in mbar
     - P7 = pressure from sensor 7 in mbar
     - P8 = pressure from sensor 8 in mbar
     - P9 = pressure from sensor 9 in mbar
     - P10 = pressure from sensor 10 in mbar
     - P11 = pressure from sensor 11 in mbar
     - P12 = pressure from sensor 12 in mbar
     - P13 = pressure from sensor 13 in mbar
     - P14 = pressure from sensor 14 in mbar
     - P15 = pressure from sensor 15 in mbar
     - P16 = pressure from sensor 16 in mbar
     - T = temperature in degrees Celsius

2. IMU_20190517.txt
     This file contains the raw IMU data from the PMM for the experiment on May 17, 2019
     - Date = date of sample
     - Time = time of sample
     - yaw = orientation of the IMU in the yaw direction, measured in degrees
     - pitch = orientation of the IMU in the pitch direction, measured in degrees
     - roll = orientation of the IMU in the roll direction, measured in degrees

3. PMM_20210202.txt
     This file contains the raw data from the PMM for the experiment on February 1-2, 2021
     - Date = date of sample
     - Time = time of sample
     - P1 = pressure from sensor 1 in mbar
     - P2 = pressure from sensor 2 in mbar
     - P3 = pressure from sensor 3 in mbar
     - P4 = pressure from sensor 4 in mbar
     - P5 = pressure from sensor 5 in mbar
     - P6 = pressure from sensor 6 in mbar
     - P7 = pressure from sensor 7 in mbar
     - P8 = pressure from sensor 8 in mbar
     - P9 = pressure from sensor 9 in mbar
     - P10 = pressure from sensor 10 in mbar
     - P11 = pressure from sensor 11 in mbar
     - P12 = pressure from sensor 12 in mbar
     - P13 = pressure from sensor 13 in mbar
     - P14 = pressure from sensor 14 in mbar
     - P15 = pressure from sensor 15 in mbar
     - P16 = pressure from sensor 16 in mbar
     - T = temperature in degrees Celsius

4. IMU_20210202.txt
     This file contains the raw IMU data from the PMM for the experiment on February 1-2, 2021
     - Date = date of sample
     - Time = time of sample
     - yaw = orientation of the IMU in the yaw direction, measured in degrees
     - pitch = orientation of the IMU in the pitch direction, measured in degrees
     - roll = orientation of the IMU in the roll direction, measured in degrees

5. PMM_20211026.txt
     This file contains the raw data from the PMM for the experiment on October 26-27, 2021
     - Date = date of sample
     - Time = time of sample
     - P1 = pressure from sensor 1 in mbar
     - P2 = pressure from sensor 2 in mbar
     - P3 = pressure from sensor 3 in mbar
     - P4 = pressure from sensor 4 in mbar
     - P5 = pressure from sensor 5 in mbar
     - P6 = pressure from sensor 6 in mbar
     - P7 = pressure from sensor 7 in mbar
     - P8 = pressure from sensor 8 in mbar
     - P9 = pressure from sensor 9 in mbar
     - P10 = pressure from sensor 10 in mbar
     - P11 = pressure from sensor 11 in mbar
     - P12 = pressure from sensor 12 in mbar
     - P13 = pressure from sensor 13 in mbar
     - P14 = pressure from sensor 14 in mbar
     - P15 = pressure from sensor 15 in mbar
     - P16 = pressure from sensor 16 in mbar
     - T = temperature in degrees Celsius

4. IMU_20211026.txt
     This file contains the raw IMU data from the PMM for the experiment on October 26-27, 2021
     - Date = date of sample
     - Time = time of sample
     - yaw = orientation of the IMU in the yaw direction, measured in degrees
     - pitch = orientation of the IMU in the pitch direction, measured in degrees
     - roll = orientation of the IMU in the roll direction, measured in degrees

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

    This file contains the raw data from the Pressure Stick for the experiment on February 1-2, 2021
    - Date = date of sample
    - Time = time of sample
    - P1 = pressure from sensor 1 (topmost sensor) in mbar, sensor 1 is about 25 cm above the sediment bed
    - P2 = pressure from sensor 2 in mbar, sensor 2 is about 15 cm above the sediment bed
    - P3 = pressure from sensor 3 in mbar, sensor 3 is about 9 cm above the sediment bed
    - P4 = pressure from sensor 4 in mbar, sensor 4 is about 3 cm above the sediment bed
    - P5 = pressure from sensor 5 in mbar, sensor 5 is about 3 cm in the sediment bed
    - P6 = pressure from sensor 6 in mbar, sensor 6 is about 13 cm in the sediment bed
    - P7 = pressure from sensor 7 in mbar, sensor 7 is about 28 cm in the sediment bed
    - P8 = pressure from sensor 8 (bottom-most sensor) in mbar, sensor 8 is about 43 cm in the sediment bed
    - T1 = temperature from sensor 1 (topmost sensor) in degrees Celsius, sensor 1 is about 25 cm above the sediment bed
    - T2 = temperature from sensor 2 in degrees Celsius, sensor 2 is about 15 cm above the sediment bed
    - T3 = temperature from sensor 3 in degrees Celsius, sensor 3 is about 9 cm above the sediment bed
    - T4 = temperature from sensor 4 in degrees Celsius, sensor 4 is about 3 cm above the sediment bed
    - T5 = temperature from sensor 5 in degrees Celsius, sensor 5 is about 3 cm in the sediment bed
    - T6 = temperature from sensor 6 in degrees Celsius, sensor 6 is about 13 cm in the sediment bed
    - T7 = temperature from sensor 7 in degrees Celsius, sensor 7 is about 28 cm in the sediment bed
    - T8 = temperature from sensor 8 (bottom-most sensor) in degrees Celsius, sensor 8 is about 43 cm in the sediment bed 

2. PS_20211026.txt

    This file contains the raw data from the Pressure Stick for the experiment on October 26-27, 2021
    - Date = date of sample
    - Time = time of sample
    - P1 = pressure from sensor 1 (topmost sensor) in mbar, sensor 1 is about 19 cm above the sediment bed
    - P2 = pressure from sensor 2 in mbar, sensor 2 is about 9 cm above the sediment bed
    - P3 = pressure from sensor 3 in mbar, sensor 3 is about 3 cm above the sediment bed
    - P4 = pressure from sensor 4 in mbar, sensor 4 is about 3 cm in the sediment bed
    - P5 = pressure from sensor 5 in mbar, sensor 5 is about 9 cm in the sediment bed
    - P6 = pressure from sensor 6 in mbar, sensor 6 is about 19 cm in the sediment bed
    - P7 = pressure from sensor 7 in mbar, sensor 7 is about 34 cm in the sediment bed
    - P8 = pressure from sensor 8 (bottom-most sensor) in mbar, sensor 8 is about 49 cm in the sediment bed
    - T1 = temperature from sensor 1 (topmost sensor) in degrees Celsius, sensor 1 is about 19 cm above the sediment bed
    - T2 = temperature from sensor 2 in degrees Celsius, sensor 2 is about 9 cm above the sediment bed
    - T3 = temperature from sensor 3 in degrees Celsius, sensor 3 is about 3 cm above the sediment bed
    - T4 = temperature from sensor 4 in degrees Celsius, sensor 4 is about 3 cm in the sediment bed
    - T5 = temperature from sensor 5 in degrees Celsius, sensor 5 is about 9 cm in the sediment bed
    - T6 = temperature from sensor 6 in degrees Celsius, sensor 6 is about 19 cm in the sediment bed
    - T7 = temperature from sensor 7 in degrees Celsius, sensor 7 is about 34 cm in the sediment bed
    - T8 = temperature from sensor 8 (bottom-most sensor) in degrees Celsius, sensor 8 is about 49 cm in the sediment bed 

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

    This file contains offshore wave data from [Jeffrey's Ledge waverider buoy (station 44098) from the National Data Buoy Center (NDBC)](https://www.ndbc.noaa.gov/station_page.php?station=44098) throughout the October 2021 experiment (October 26th 2021 00:26:00 - October 27th 2021 23:56:00). Please see [Description of Measurements](https://www.ndbc.noaa.gov/measdes.shtml) for a discussion of each of the variables in this file.
