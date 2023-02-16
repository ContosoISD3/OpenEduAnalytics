# Power BI Template

## Dashboard Explanation
The Reading Progress module Power BI template consists of an Explanation page and a Reading Fluency page. This Power BI visualizes reding fluency related user activities in Reading Progress:
- Reading Accuracy Rate: Shows the reading accuracy trend over a period of time.
- Reading Pace: Shows the reading pace trend over a period of time.
- Breakdown of Reading Fluency by School: Shows the reading accuracy score, word count and number of attempts at a schoool level.
- Reading Error Categorization: Shows the breakdown of reading accuracy and its associated errors at a grade level.
- Filter by school, class and date.

![](https://github.com/microsoft/OpenEduAnalytics/blob/main/modules/module_catalog/Reading_Progress/docs/images/Reading_Progress_Dashboard.png)


## Data Model
The Reading Progress module is made up of 2 tables where Student_pseudo is the dimension table and ReadingProgress_pseudo is the fact table.
![](https://github.com/microsoft/OpenEduAnalytics/blob/main/modules/module_catalog/Reading_Progress/docs/images/Reading_Progress_Data_Model.png)


## Power BI Setup Instructions

#### Power BI with imported test data:
1. Download the PBIX file.
2. Open the link locally on your computer and explore this module's test data. 

#### Power BI with direct query of data on your data lake:
1. Complete the [module setup instructions](https://github.com/microsoft/OpenEduAnalytics/tree/main/modules/module_catalog/Reading_Progress#module-setup-instructions).
2. Download the PBIX file.
3. The dashboard visuals may not load. You will need to switch your Synapse workspace serverless SQL endpoint by:
   * Select menu item File > Options and settings > Data source settings.

![](https://github.com/microsoft/OpenEduAnalytics/blob/main/packages/package_catalog/Hybrid_Engagement/docs/images/pbi_instructions_p1_options_and_settings.png)

    - Select Change Source...
| <img src="https://github.com/microsoft/OpenEduAnalytics/blob/main/modules/module_catalog/Clever/docs/images/pbi%20change%20source.png" width="600"> | 
|-|
    - Enter your Synapse workspace SQL server endpoint. This can be found on your Synapse workspace information page in the Azure portal.
<kbd> 
    <img src="https://github.com/microsoft/OpenEduAnalytics/blob/main/modules/module_catalog/Clever/docs/images/pbi%20sql%20endpt.png" width="600">
</kbd>
<kbd> 
    <img src="https://github.com/microsoft/OpenEduAnalytics/blob/main/modules/module_catalog/Clever/docs/images/synapse%20sql%20enpt.png" width="600"> 
</kbd>
