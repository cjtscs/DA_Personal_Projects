# Australian Aged Care Mandatory Quality Indicator Program Dashboard
Analysed, calculated and presented the quality performance of an aged care provider.

_Download the **Mock Aged Care PBI.pbix** file to view the entire PowerBI report. All data sources are linked to the .csv files in this repository. The "Mock Care Homes" data set is composed of synthetic data created by the repository owner designed to imitate possible real-world data from aged care management and payroll systems._

## User Story & Dashboard Requirements
This user story outlines the specifications for creating a quality indicator performance dashboard using PowerBI to assist the Clinical Manager and upper management to keep track and report on the quality performance of Mock Care Homes.

## Key Requirements
The Clinical Manager requires a dashboard that presents the real-time performance of the current quarter with the ability to view historical quarters as well. The calculations for the indicator percentages must adhere to the requirements of the 1 April 2023 requirements of the National Aged Care Mandatory Quality Indicator Program (https://www.health.gov.au/resources/collections/national-aged-care-mandatory-quality-indicator-program-manual). Further, granular data must also be available for viewing and downloading for reporting or audit purposes. 

### Quality Indicator Dashboard
- Calculate and present the current and historical quality performance based on the 11 indicators by quarter
- Indicate whether each of the indicators has improved or deteriorated from the previous quarter 

![image](https://github.com/user-attachments/assets/db4dbd47-9943-481b-b8dc-b2edacc25ecd)


### QI Trends Chart
- Present the quality indicators in a trend line showing all quarters
- The 11 quality indicators can be grouped based on the groupings of the Department of Health and Aged Care

![image](https://github.com/user-attachments/assets/fc5fd091-9d67-41c6-bfcb-cc8e6eef4d14)
 

### Data Viewer Page
- In one page, present all granular data used by the report to calculate the quality indicators
![image](https://github.com/user-attachments/assets/ad0241c4-2e92-4390-851d-36e3adb26021)


## Design and Interactivty Requirements
- To prevent miscalculation of the quality indicator percentages by users, disallow the use of slicers and filters. Only the selection of quarters should be allowed for users
- To prevent misinterpretation of the figures, include tooltips to assist users in understanding the indicators
![image](https://github.com/user-attachments/assets/f3acde33-2640-451e-9c89-ffa07ee36e5e)
