# Power-BI-Project

## Data Manipulation and Reporting with Power BI

### Description

Zomato is a restaurant aggregation and meal delivery service operating globally. This project involves examining Zomato's data to accurately assess business performance. The goal is to construct an interactive Power BI report that provides insights into various aspects of the restaurant industry.

The data is available in multiple Excel files, each containing information about restaurants in a specific continent. The project aims to:

1. Derive data on the total number of restaurants worldwide, including continents, countries, and cities.
2. View global data with the ability to drill down to a granular level.
3. Extract data on restaurants with the highest average customer ratings.
4. Identify restaurants with the lowest average costs.
5. Filter and view information based on geographical dimensions, services offered, and average rating slabs.
6. Identify restaurants serving the most cuisines.
7. Design a multi-page report with easy navigation that aligns with Zomato's theme.
8. Ensure accessibility from both web browsers and mobile devices.

### Aim of the Project

The aim is to create an interactive Power BI report for Zomato to quickly assess and derive insights from the provided data.

### Steps to Complete the Project

1. **Import Data:**
   - Import data from all available Excel files.

2. **Data Transformation:**
   - Correct City column names (e.g., "Sí£o Paulo" to "São Paulo").
   - Ensure city names are not ambiguous (e.g., "Cedar Rapids/Iowa City" to "Cedar Rapids").
   - Address any other inconsistencies in the data.

3. **Column Cleanup:**
   - Remove any unused columns.

4. **Create Restaurant Name and Address Columns:**
   - Create two columns to display the Restaurant Name and Restaurant Address.

5. **Cuisine Table:**
   - Make a separate table for the list of cuisines each restaurant serves.

6. **Country-Code Table:**
   - Ensure the Country-Code table only includes unique and non-blank values.

### Steps Using DAX

1. **Rating Color Column:**
   - Add a Rating color column in an appropriate table based on the given format.

   | Aggregate rating | Rating color  |
   |------------------|---------------|
   | Above 4.5        | Dark Green    |
   | 4 to 4.4         | Green         |

2. **Create Measures:**
   - Create the following measures in appropriate tables:
      a. Restaurant count
      b. Average cost
      c. Average rating
      d. Cuisine count

3. **Continent Column in Country Code Table:**
   - Create a new column in the Country Code table named "Continent" and use the provided convention.

   Note: The mapping is continent - country, for example ''Africa – South Africa''.

### Instructions for Users

1. **Clone the Repository:**
   - Clone this repository to your local machine.

2. **Data Preparation:**
   - Follow the provided steps for data import and transformation.

3. **DAX Measures:**
   - Implement the suggested DAX measures.

4. **Continent Column:**
   - Create the "Continent" column in the Country Code table.

5. **Explore the Power BI Report:**
   - Open the Power BI report to explore and analyze the Zomato data.

6. **Feedback:**
   - Feel free to provide feedback or suggestions for improvement.

Enjoy exploring the world of Zomato data with Power BI! 🌐📊
