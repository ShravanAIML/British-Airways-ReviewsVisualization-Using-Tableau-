# British-Airways-ReviewsVisualization-Using-Tableau

### **Steps to Build the Dashboard**

**1. Join Tables**  
    Merge the BA Reviews table with the Countries table using the Place column from BA Reviews and the Country 
    column from Countries.  
    Ensure the join is accurate and all necessary fields are included.

**2. Average Metric By Country (Map)**  
    Use the Place column to create a map visualization.  
    Add a Pick a Metric parameter to allow users to select metrics from the dataset 
    (e.g., Overall Rating, Cabin Staff Service).  
    Create a calculated field to dynamically filter the selected metric.  
    Apply color coding based on the average value of the selected metric for each country.  
    Add filters for Month of Date, Seat Type, Traveler Type, and Continent.

**3. Average Metric By Month (Line Chart)**  
    Plot Month-Year on the X-axis and the selected metric on the Y-axis.  
    Ensure the chart updates dynamically based on the selected metric.

**4. Average Metric By Aircraft (Dual Bar Chart)**  
    Create a dual bar chart for each aircraft type:  
       Bar 1: Average value of the selected metric.  
       Bar 2: Review Count.  
    Use contrasting colors to differentiate between the two metrics.

**5. Build the Dashboard**  
    **Layout**:  
    **Left Sidebar**: Add filters for Pick a Metric, Month of Date, Seat Type, Traveler Type, Aircraft Type
    and Continent.  
    **Top Section**: Display summary metrics like the average ratings for services.  
    **Main Section**: Include the Map, Line Chart, and Dual Bar Chart.  
    Link all visualizations to the filters for interactivity.

**Filters Used**  
Pick a Metric (e.g., Overall Rating, Value for Money)  
Month of Date  
Seat Type (Economy, Business, Premium Economy, etc.)  
Traveler Type (Business, Couple Leisure, Family Leisure, etc.)  
Aircraft Type  
Continent  
