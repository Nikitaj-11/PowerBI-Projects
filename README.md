# Healthcare Waitlist Analysis - Dashboard

## Project Description
This Power BI Dashboard was developed to track the current status and analyze historical trends of patient waiting lists in both inpatient and outpatient categories. The dashboard provides detailed insights into specialty-level and age profile analyses from the years 2018 to 2021. The key metrics include average and median waiting list times, and the dashboard features both a summary page and a detailed analysis page for comprehensive data exploration.

### Objectives
- Track the current status of the patient waiting list.
- Analyze historical monthly trends in inpatient and outpatient categories.
- Provide detailed specialty-level and age profile analysis.
- Present data from 2018 to 2021.

### Key Metrics
- Average & Median Waiting List
- Current Total Wait List
  
### Views
- Summary Page: High-level overview of key metrics and trends.
- Detailed Page: Granular data analysis segmented by specialty and age profile.
  
### Steps Taken

1. #### Requirement Gathering
- Identify Stakeholders: Engaged with domain experts to define dashboard requirements.
- Understand Business Objectives: Outlined goals through meetings with stakeholders, understanding how the dashboard would support business objectives.
- High-Level Data Study: Assessed data sources, volume, and quality, identifying potential issues like missing values or anomalies.
- Define Scope: Documented key metrics, KPIs, and deployment timelines, ensuring a buffer for deadlines to manage expectations effectively.

2. #### Data Collection
- Used a central folder to host all files required for the dashboard refresh process.
- Imported data into Power BI using the Folder connector:
  - Navigated to the folder containing Inpatient and Outpatient data.
  - Combined and loaded files to prepare them for transformation.

3. #### Data Transformation
- Conducted data transformations in the Power Query Editor:
  - Renaming Columns: Ensured consistent column naming across datasets.
  - Rearranging Columns: Matched column order between inpatient and outpatient datasets.
  - Appending Tables: Combined inpatient and outpatient data into a single table ("All_Data").
  - Cleaning Data: Replaced redundant values and removed trailing blanks using the Replace and Trim functions.

4.  #### Data Modelling
- Established relationships between tables using the specialty mapping file to group specialties into manageable buckets.
- Ensured accurate relationships and filtering between datasets for effective reporting.

5. #### Visualization Blueprint
- Created a wireframe of the dashboard and received stakeholder approval before development.
  
6. #### Dashboard Layout & Design
- Enabled gridlines and snap-to-grid for visual alignment.
- Used DAX to create measures for key calculations:
  - Latest Month Wait List
  - Previous Year Wait List
  - Average and Median Wait List
- Designed visual elements including doughnut charts, clustered column charts, and line charts to present data effectively.

7. #### Adding Interactivity
- Added slicers for dynamic filtering.
- Implemented navigation buttons and tooltips for enhanced user experience.

8. #### Testing and Sharing
- Conducted UAT sessions to identify and resolve bugs.
- Implemented Row Level Security for data access control before publishing the dashboard.

9. #### Routine Refresh & Maintenance
- Established a monthly refresh process for data updates.
- Documented a maintenance plan for ongoing support and enhancements.

### Tools & Technologies
- Data Sources: Excel/CSV, SQL Server
- Visualization Tool: Power BI
- Transformation Tool: Power Query Editor
- Design Tools: PowerPoint, Canva

### Final Notes
This project showcases a systematic approach to building a Power BI dashboard, from initial requirement gathering to deployment and maintenance. The dashboard provides actionable insights into patient waiting lists, enabling healthcare administrators to make data-driven decisions.
