✅ Power BI Interview Questions and Answers (1–20)
1. What is Power BI Service?  
Power BI Service is a cloud-based analytics platform where users can create dashboards, share reports,
collaborate with teams, schedule data refreshes, and manage security. It enables real-time reporting and integrates
with various data sources.

3. What are the limitations of Power BI?  

Can't share reports from Power BI Desktop directly (needs Service or Pro account)  

Limited data refreshes (8/day in Pro, 48/day in Premium)  

Storage limitations (10 GB per user in Pro)  

Limited modeling capabilities for large datasets in Direct Query mode  

Premium features are costly  

3. What is Power Pivot?    
Power Pivot is a data modeling component in Power BI. It allows users to create relationships, calculated columns, and DAX measures   
on large datasets for advanced data analysis.

4. What is Power View?  
Power View is a data visualization tool in Power BI that allows users to create interactive charts, graphs, maps, and other visuals.  

5. What is Power Query?
Power Query is used for data transformation and preparation. It allows connecting, cleaning, shaping, and transforming data before   
it is loaded into the model. It's powered by the M language.

6. Commonly used tasks in Power Query Editor?  

Connecting to data sources 

Removing duplicates  

Changing data types  

Pivoting/unpivoting columns  

Merging and appending queries  

Creating custom columns with formulas  

7. What are the components of Power BI?  

Power Query: Data transformation  

Power Pivot: Data modeling  

Power View: Visualizations

Power Map: Geospatial visualizations

Power Q&A: Natural language queries

8. What are the building blocks of Power BI?

Visualizations

Datasets

Reports

Dashboards

Tiles

9. What is the data size limit in Power BI?

Power BI Pro: 1 GB per dataset

Power BI Premium: Up to 10 GB per dataset

10. What is DirectQuery?
In DirectQuery, Power BI doesn't import the data. Instead, it queries the source database in real-time, which is useful for large datasets and live reporting needs.

11. How many records can Power BI Desktop display?
It can display up to 1 million rows in a table visual, but the data model can hold much more depending on memory.

12. What data sources have you worked on?
Common ones include Excel, SQL Server, Azure SQL, CSV files, SharePoint, Web APIs, Oracle, and more.

13. What is a dashboard?
A dashboard is a single-page, real-time view of your most important metrics, created by pinning visuals from multiple reports.

14. Can you delete a dataset from a workspace?
Yes, you can delete a dataset from a workspace, but once it's part of a published app, you must unpublish the app to delete it.

15. What are the features of Power BI Service?

Schedule data refresh

Create and publish dashboards

Share reports with users

Apply Row Level Security (RLS)

Collaborate via workspaces

16. What are relationships in Power BI and types?
Relationships define how tables connect using keys. Types:

Active Relationship: Default, used in visuals

Inactive Relationship: Can be used with DAX
Also categorized by cardinality: One-to-One, One-to-Many, Many-to-Many

17. What is Cardinality?
Cardinality defines the relationship type based on uniqueness of values in columns:

One-to-One

One-to-Many

Many-to-Many

18. What is Cross Filtering?
It determines how filters propagate across relationships. Two modes:

Single: Filters flow from parent to child

Both (Bi-directional): Filters affect both tables

19. Can you delete reports/datasets from workspace?
Yes, but for published apps, you need to unpublish first.

20. Is a dataset different from a report?
Yes. A dataset is the data model. A report is the visualization layer built on top of a dataset.

✅ Power BI Interview Questions and Answers (21–40)
21. What is a Dashboard in Power BI?
A Dashboard is a one-page canvas that consolidates visuals (tiles) from multiple reports and datasets, offering a high-level overview of key metrics.

22. Can we create a dashboard using visuals from multiple report pages or reports?
Yes. Dashboards can combine visuals from different report pages and even different reports.

23. What is a Dataset?
A Dataset is a collection of data used to create reports and visuals in Power BI. It can be sourced from files, databases, or cloud services.

24. Can we import data directly into Power BI Service?
Yes. Using the "Get Data" option in Power BI Service, you can import data from files, OneDrive, databases (like Azure SQL), and even from SaaS connectors.

25. What is the difference between a Dataset and Power BI Dataset?
There is no difference. Both refer to the structured data model used in Power BI.

26. Can we use DirectQuery with Excel?
No, Excel files must be imported. DirectQuery is supported for databases like SQL Server, Azure SQL, etc.

27. Can we retrieve data using SQL scripts in Power BI?
Yes. When connecting to SQL Server or similar sources, you can enter a custom SQL query to fetch specific data.

28. What is a Power BI Report?
A report is a collection of visuals, filters, and pages created on top of a single dataset. Reports are saved as .pbix files.

29. What are the types of sharing methods in Power BI?

Email Sharing

Apps

Content Packs

Sharing from Power BI Service (workspace)

30. How can you import local images into Power BI Desktop?
Convert the image to Base64 format and use it in a table with Image URL as the data category. Alternatively, store images in a folder and import using "Folder" as a source.

31. Power BI Pro vs Power BI Premium – What's the difference?

Feature	Power BI Pro	Power BI Premium
Max Storage	10 GB/user	100 TB shared
Dataset Size	1 GB	10 GB
Refreshes/day	8	48
Cost	Per-user license	Capacity-based license
Sharing	Yes	Yes
Incremental Refresh	No	Yes
32. What is RLS (Row Level Security)?
RLS restricts data access for users based on their roles. It's configured using DAX filters in Power BI Desktop and enforced in the Service.

33. What’s the difference between USERNAME() and USERPRINCIPALNAME() in DAX?

USERNAME() → DOMAIN\username

USERPRINCIPALNAME() → user@domain.com
Useful in dynamic RLS scenarios to identify the logged-in user.

34. Can RLS restrict access to specific columns or measures?
No. RLS can only restrict access to rows, not columns or measures.

35. Can RLS hide detailed data but show summaries?
No. If users have access to rows, they can view all columns in those rows, including summarized and detailed views.

36. What is Static RLS?
Roles are hardcoded based on predefined filters. Example: SalesRole only sees data for "Region = East".

37. What is Dynamic RLS?
Filters are based on logged-in user information, like email or username. It enables more scalable security models.

38. If RLS is defined in the Power BI Service, will it still work after publishing from Desktop?
No. You must reconfigure roles in Power BI Desktop and republish. Roles created only in the service won’t be preserved.

39. What is a Visual in Power BI?
A Visual is a graphical representation of data such as charts, maps, tables, and KPIs used in reports and dashboards.

40. Can you define RLS for Analysis Services live connections?
RLS must be defined within the Analysis Services model itself. Power BI cannot configure RLS for live connections—only for imported models.

✅ Power BI Interview Questions and Answers (41–60)
41. Can I use RLS to limit the columns or measures accessible by users?
No. RLS (Row-Level Security) only controls which rows a user can see. It does not restrict access to specific columns or measures.

42. Can RLS hide detailed data while allowing summarized data to be visible?
No. If a user can see a row of data, they can access both the detailed and summarized views for that row.

43. Can I use a custom URL as a hyperlink in a table or matrix visual?
Yes, but with limitations. You can display a clickable link using the Web URL data category. To customize link text, you’ll need to create a new column with HTML-style formatting in some cases.

44. What is a report in Power BI?
A report is a collection of interactive visuals, filters, and pages built on a single dataset. It provides detailed data exploration and can have multiple pages (like tabs in Excel).

45. Can we delete datasets from a Power BI Pro workspace?
Yes. You can delete datasets from a workspace, but if it’s part of a published app, you must unpublish the app first.

46. Can we create a dashboard using visuals from multiple pages of a report?
Yes. You can pin visuals from different pages of a single report to a dashboard.

47. Can we create a dashboard using visuals from multiple reports?
Yes. Power BI dashboards can include visuals from multiple reports and datasets.

48. Can reports be created directly in the Power BI Service?
Yes, basic reports can be created in the Power BI Service by connecting to datasets available in the workspace.

49. Can you create calculated columns and measures in Power BI Service?
No. Calculated columns and measures must be created in Power BI Desktop. They are not editable or creatable in the Power BI Service.

50. What are the types of filters in Power BI?

Visual-level Filter – Applies only to a single visual.

Page-level Filter – Applies to all visuals on a report page.

Report-level Filter – Applies to all pages in the report.

51. What is the difference between Import, DirectQuery, and Live Connection?

Import Mode: Data is loaded into Power BI. Fastest performance.

DirectQuery: Data remains in the source; Power BI queries it in real-time. Good for large datasets.

Live Connection: Similar to DirectQuery, used for Analysis Services (SSAS); no data modeling allowed in Power BI.

52. What is the difference between Append and Merge in Power Query?

Append: Combines tables vertically (adds rows). Like SQL UNION ALL.

Merge: Combines tables horizontally (adds columns) using a join key. Like SQL JOIN.

53. What is a Gateway in Power BI? Types and use?
A Gateway connects on-premises data sources to the Power BI Service.
Types:

Personal Mode: For one user. Used for import only.

Enterprise (On-Premises): Supports multiple users, DirectQuery, Live Connections.
Used to refresh data securely from local sources.

54. What is a Slicer and Sync Slicer in Power BI?

Slicer: A visual filter on a report page for filtering visuals dynamically.

Sync Slicer: Enables a slicer’s filter to apply across multiple pages in a report.

55. What are Bookmarks in Power BI?
Bookmarks capture the current state of a report page (filters, slicers, visuals) and allow you to return to that exact view later. Useful for storytelling or navigation.

56. What is "New Group" in Power BI?
New Group allows you to group values in a field manually into categories.
Example: Grouping several countries into regions like "Europe" or "Asia".

57. How can you create a virtual table in DAX?
Virtual tables can be created using DAX functions like:

SUMMARIZE()

ADDCOLUMNS()

CALCULATETABLE()

VALUES()
These tables exist only during evaluation and are not physically stored.

58. What are Aggregation functions in DAX?
Common DAX aggregation functions include:

SUM()

AVERAGE()

MIN()

MAX()

COUNT()

DIVIDE()

59. What are Iterating DAX functions?
These functions operate row by row and include:

SUMX(), AVERAGEX(), MINX(), MAXX()

COUNTX(), RANKX(), FILTERX()

ADDCOLUMNS(), GENERATE()

60. Can you change a column's value dynamically in Power BI?
Yes, using parameters or what-if parameters, you can dynamically change column values or calculations.

✅ Power BI Interview Questions and Answers (61–80)
✨ Beginner to Pro – Fully Explained

61. What is User Acceptance Testing (UAT) in Power BI?
User Acceptance Testing ensures the report meets business requirements.
✅ Checks include:

Data accuracy

Filter behavior

Layout and UX

Load times and performance
It’s done by business users before final deployment to confirm the report is useful and correct.

62. Can we import data directly to Power BI Service?
Yes.
Go to Power BI Service → Get Data → Choose source (e.g., Excel, CSV, Azure SQL, SharePoint, etc.).
Use this when you don't want to go through Power BI Desktop.

63. Can we use DirectQuery for databases?
Yes.
Databases like SQL Server, Azure SQL, Oracle, and others support DirectQuery. This lets Power BI pull data in real time without importing it.

64. What is a Parameter in Power BI?
A Parameter allows dynamic filtering or control.
Example: You can create a parameter for “Region” so the user can switch between North/South and filter data accordingly — even before loading it into the model.

65. How to implement a Parameter?
Steps:

Go to Power Query Editor → Manage Parameters → New Parameter

Define name, values, default

Use it in filtering or as input to SQL queries
👉 Used in dynamic data loading, what-if analysis, or slicing visuals.

66. What are the 3 key components of Power BI?

Power BI Desktop – Build reports, models, visuals

Power BI Service (Cloud) – Share, refresh, secure, collaborate

Power BI Mobile – View dashboards on phone/tablet

67. Difference between Calculated Column and Measure?

Feature	Calculated Column	Measure
When it calculates	On data load	When queried (on-demand)
Stored in model	Yes	No
Uses Row Context	Yes	No
Use case	Filtering, grouping	KPIs, totals, aggregations
Example	Year = YEAR(Date[OrderDate])	TotalSales = SUM(Sales[Amount])
✅ Tip: Use measures whenever possible to save memory and improve performance.

68. Do we need a Pro license to create an App Workspace?
Yes. You need a Power BI Pro license to create and manage workspaces, publish apps, and collaborate with teams.

69. What is M Language?
M is the data transformation language used by Power Query.
It’s case-sensitive and functional (like F#). You don’t need to be an expert, but understanding how Power Query steps are generated helps in debugging or customizing transformations.

70. What are the ways to share reports in Power BI?

Email sharing – Direct link

App sharing – Package reports/dashboards to distribute

Content Pack – Older way to bundle datasets + visuals

Publish to Web – Public sharing (not secure)

Embed in SharePoint / Teams

71. Content Pack vs App?

Feature	Content Pack	App
Custom selection	Yes	No – shares all content in workspace
UI & UX	Basic	Better navigation & branding
Modern usage	Outdated	Recommended way to share
72. How to create mobile-compatible reports?
After building the report:
Go to View → Phone Layout
Drag and drop visuals to create a responsive layout.
👉 This version loads faster on mobile and is optimized for touch interaction.

73. How to configure scheduled data refresh?

Go to Power BI Service

Click dataset → Settings

Set credentials for data source

Enable Scheduled Refresh (up to 8/day in Pro, 48/day in Premium)

74. What is a Content Pack?
A pre-packaged bundle of dashboards, datasets, and reports shared across an organization or group.
📦 Like a "starter kit" for BI users.

75. Why use a Content Pack?
For quickly deploying standardized reports to users without having them build from scratch.

76. What is Edit Interaction in Power BI?
It controls how visuals react when you select something in another visual.
🔧 Options:

Filter

Highlight

None
Go to Format → Edit Interactions to configure.

77. What types of interactions exist in Power BI visuals?

Drill down – View detailed levels

Roll up – Collapse levels

Highlight – Emphasize selected data

Filter – Show only selected data

None – No effect from other visuals

78. Explain types of charts used in Power BI.

Bar/Column Charts – Compare across categories

Line Charts – Time-series trends

Pie/Donut – Show parts of a whole

Tree Map – Hierarchical data in rectangles

Waterfall – Breakdown of totals by steps

Gauge/KPI – Performance indicators

Combo Chart – Bar + Line in one chart

Map – Geographical data

79. What is the file format of Power BI files?
Power BI saves files with the extension .pbix
For templates: .pbit

80. Types of joins available in Power Query (Merge)?

Inner Join – Matches in both

Left Outer Join – All from first + matches from second

Right Outer Join – All from second + matches from first

Full Outer Join – All from both

Anti Joins – Return non-matching rows

