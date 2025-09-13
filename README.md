## Uber-Data-Analysis-Project

# DAHBOARD 1: OVERVIEW ANALYSIS
Analyse Uber trip data using Power BI to gain insights into booking trends, revenue, and trip efficiency, helping stakeholders make data-driven decisions.
KPI’s
1.	Total Bookings – How many trips were booked over a given period?
2.	Total Booking Value – What is the total revenue generated from all bookings?
3.	Average Booking Value – What is the average revenue per booking?
4.	Total Trip Distance – What is the total distance covered by all trips?
5.	Average Trip Distance – How far are customers traveling on average per trip?
6.	Average Trip Time – What is the average duration of trips?

CHART’s
Create a Measure Selector using a Disconnected Table with the following values:
•	Total Bookings
•	Total Booking Value
•	Total Trip Distance
Then, use a measure to dynamically update the visualizations based on user selection.
By Payment Type (Card, Cash, Wallet, etc.)
By Trip Type (Day/Night)

Other Implementation Enhancements for Uber Trip Analysis Dashboard
	Bookmark for Data Details 
•	Add a "Data Details" bookmark to display a pop-up or side panel explaining:
o	Meaning of key metrics (Total Bookings, Total Trip Distance, etc.).
o	Description of tables used in the analysis.
o	Data source and refresh frequency.
	Clear Slicer Button 
•	Add a "Clear Filters" button using a blank button with a Reset Slicers action to reset all selections in one click.
•	Improves user experience for quick dashboard resets.
	Download Raw Data Button 
•	Add a button to export raw data in CSV or Excel format.
•	Use Power Automate or built-in Power BI Export functionality.
•	Enables users to analyse raw data outside Power BI if needed.

# DAHBOARD 2: TIME ANALYSIS
To understand trip patterns based on time, Uber needs to analyse ride demand and trends across different time intervals. This dashboard will help in optimizing operations, pricing, and driver availability.
Global Dynamic Measure (Filters All Charts)
A measure selector will be created for:
✔ Total Bookings
✔ Total Booking Value
✔ Total Trip Distance

# DAHBOARD 3: DETAILS TAB
To provide in-depth insights and allow users to explore granular data, a Grid Tab will be created. This tab will enable drill-through functionality, allowing users to access detailed records based on selections made in other dashboards.
