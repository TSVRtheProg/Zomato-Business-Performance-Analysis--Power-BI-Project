# Zomato Business Performance Analysis

This Power BI project meant to help Zomato, a global restaurant aggregation and meal delivery service, evaluate its business success by aggregating restaurant data from many nations and continents. The goal is to create an interactive Power BI report that would enable Zomato's management to gain crucial insights into their operations, including restaurant performance, regional trends, customer reviews, and more.

The report will enable Zomato to dive down from a global scale to more detailed levels, allowing them to make more informed decisions about how to enhance operations, services, and satisfaction with customers.

## Objective
The main objectives of this project are:

--> Aggregate Zomato’s data globally, including key metrics such as restaurant count, average cost, average rating, and cuisine count.

--> Create a consolidated and interactive Power BI report that enables data exploration across multiple dimensions like continents, countries, cities, and restaurant services.

--> Utilize DAX measures to analyze key metrics and create dynamic, color-coded ratings and aggregations.

## Project Tasks
1. Data Import and Transformation
Import Data: Load data from multiple Excel files, each containing information about restaurants in different continents.

Remove Unnecessary Columns: Clean up the data by removing columns that do not contribute to the analysis.

Create Restaurant Name and Address Columns: Generate new columns to display the restaurant name and restaurant address.

2. DAX Implementation
Create Rating Slab: Using DAX, categorize the ratings into two groups:

Above 4.5: Dark Green

4 to 4.4: Green

### Measures to Create:
Restaurant Count: Calculate the total number of restaurants in each region.

Average Cost: Compute the average cost for meals at each restaurant.

Average Rating: Calculate the average customer rating for restaurants.

Cuisine Count: Count the number of distinct cuisines served by each restaurant.

3. Continent and Country Code Mapping
Create “Continent” Column: Add a new column in the Country Code table to map each country to its respective continent (e.g., Africa – South Africa).

4. Cuisine List Table
Separate Cuisine Table: Create a table for the list of cuisines each restaurant serves, as this is a key dimension for analysis.

5. Geographical and Service-Based Filters
Geographical Dimensions: Filter and display data by continents, countries, and cities.

Service Filters: Filter restaurants by the services they provide, such as online ordering or reservations.

Average Rating by Color: Visualize average ratings using color slabs for quick identification of high-performing and low-performing restaurants.

6. Interactive Multi-Page Report Design
User Navigation: Design a user-friendly, interactive report with easy navigation across multiple pages, ensuring the report is intuitive for business users.

## Tools and Technologies
Power BI: For creating the report and visualizations.

DAX (Data Analysis Expressions): For creating the necessary measures and calculations.

Excel: As the source data for restaurant performance.

## How to Use
Import Data: Load all available Excel files into Power BI.

Clean and Transform Data: Remove unnecessary columns and create the necessary calculated columns and tables.

Create DAX Measures: Implement the DAX calculations for restaurant count, average rating, and other key metrics.

Design the Report: Build the Power BI report with interactive visualizations, applying filters for user-driven insights.

Publish and Share: Publish the report to the Power BI service, making it accessible for both desktop and mobile devices.


## Conclusion
By creating this thorough Power BI report, Zomato will receive vital insights into its global operations, allowing them to make data-driven decisions that improve performance and customer happiness. The ability to drill down from global metrics to more granular data will allow Zomato's leadership team to discover hidden trends, fine-tune their strategy, and provide a high-quality experience to their customers all around the world.

# Data at your fingertips, insights within reach! 📊

