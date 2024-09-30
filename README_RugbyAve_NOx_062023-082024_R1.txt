Principle Investigator, Kaiser, Jennifer B.
Georgia Institute of Technology
jennifer.kaiser@ce.gatech.edu
404-894-2644
https://kaisergroup.ce.gatech.edu/
Data collected and processed by Aryiana Moore, amoore334@gatech.edu

No use in publication without prior permission. 

Rugby Avenue Site
Location: 33.663, -84.434
Data Availability: June 8, 2023 – August 2, 2024 

Variables: Time, NO_ppb, NO2_ppb, CAPS_flag 
Explanation of variables: 
Time – Start time of 15 min average in UTC
NO_ppb – NO concentration in parts per billion
NO2_ppb – NO2 concentration in parts per billion
CAPS_flag – indicates if NO2 data is from the Aerodyne CAPS instrument or Teledyne 200A 
instrument. When CAPS_flag is 1, the NO2 data is from the Aerodyne CAPS

Information about data processing and uncertainty below. 
  NO
NO was measured using a Teledyne-API Model 200A Chemiluminescent NO/NO2/NOx analyzer. 
The instrument was calibrated 4 times throughout the campaign. Four sensitivities (all 
consistent with each other) were used to process the voltage data and a consistent zero 
was used for the entire dataset. Power outages and electrical failures have been removed 
from the dataset. 

Manufacturer listed instrument uncertainty is 0.5% and the calibration standard uncertainty
is 5% indicating a total uncertainty of 5%. The 10 min LOD is 1.2 ppb.

  NO2 
NO2 was measured using a Teledyne-API Model 200A Chemiluminescent NO/NO2/NOx analyzer and
an Aerodyne Cavity Attenuated Phase Shift (CAPS) NO2 Monitor. For the entire dataset the 
Pearson correlation between the two instruments when both were operational was 0.980. Due to 
data quality, the Aerodyne CAPS instrument data was used when available 
(indicated by CAPS_flag=1). Automatic zeros were taken every 2-4 hours and were linearly interpolated. 
The instrument was calibrated 4 times throughout the campaign (2 calibrations used, difference 
between calibrations unlikely to cause difference larger than LOD). When the Aerodyne CAPS data was 
unavailable, Teledyne NO2 was corrected using linear regression between the two instruments for near-time
periods. Power outages and electrical failures have been removed from the dataset.

Manufacturer listed instrument uncertainty for the Teledyne 200A is 0.5% and the calibration standard 
uncertainty is 10% indicating a total uncertainty of 10%. Manufacturer listed instrument uncertainty 
for the Aerodyne CAPS is 0.2% (0.1 ppb precision for NO2 concentrations less than 50 ppb) and the 
calibration standard uncertainty is 10% indicating a total uncertainty of 10%. For the CAPS, the 10 min LOD
is 3.5 ppb. Due to the correction of Teledyne 200A NO2, there is an additional +/- 10 ppb uncertainty for
June 8, 2023-Sep  30, 2023, +/- 5 ppb uncertainty for Oct 1, 2023-Jan 31, 2024, and +/- 7 ppb uncertainty
for February 1, 2024-Aug 2, 2024.  This additional error is only for Teledyne corrected data (CAPS_flag=0). 


Revisions:
R1 – Initial complete NOx dataset from Rugby Ave campaign 