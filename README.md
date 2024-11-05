# Airbnb Listing Analysis

## Project Overview

Welcome to the Airbnb Listing Analysis project! This project aims to analyze Airbnb data to extract meaningful insights about properties, pricing, customer preferences, and more. The analysis is performed using a Jupyter Notebook and a dataset containing detailed information about Airbnb listings.

The project focuses on answering key questions such as:

- Which factors affect the price of an Airbnb listing the most?
- How does location impact booking rates?
- What amenities are highly sought after by guests?

This analysis is ideal for anyone interested in learning more about data analysis, data visualization, and how data can inform better decisions for hosts, travelers, and business analysts.

## Dataset

The dataset used in this project is `Listings.csv`, which contains information on various Airbnb properties, including:

- Listing ID
- Name
- Host ID
- Host Name
- Neighborhood Group
- Neighborhood
- Latitude and Longitude
- Room Type
- Price
- Minimum Nights
- Number of Reviews
- Last Review Date
- Reviews per Month
- Calculated Host Listings Count
- Availability (number of days available in a year)

The dataset provides a comprehensive view of Airbnb listings, allowing for detailed analysis of different attributes.

## Tools and Technologies

- **Jupyter Notebook**: The primary tool used for analyzing and visualizing data.
- **Python Libraries**: Key libraries used in the analysis include:
  - **Pandas** for data manipulation and cleaning.
  - **NumPy** for numerical computations.
  - **Matplotlib** and **Seaborn** for data visualization to uncover trends.

## Key Insights from the Analysis

- **Price Determinants**: The analysis revealed that factors such as neighborhood group, room type, and availability play a significant role in determining the listing price.
- **Popular Neighborhoods**: The data indicates that neighborhoods located in central or tourist-heavy areas tend to attract more bookings and have higher prices.
- **Room Type Impact**: Listings that are entire homes or apartments generally have higher prices compared to private rooms or shared spaces.
- **Review Influence**: Listings with a higher number of positive reviews and recent reviews tend to perform better in terms of bookings.

## Analysis Workflow

The project follows these steps:

1. **Data Cleaning**: The `Listings.csv` file is loaded, and missing or inconsistent data is handled appropriately.
2. **Exploratory Data Analysis (EDA)**: Visualizations and statistical analyses are performed to understand patterns and relationships in the data.
3. **Feature Engineering**: Additional features are created to enhance the analysis, such as transforming dates into useful time-based features.
4. **Insights and Conclusions**: Based on the analysis, insights are drawn to help Airbnb hosts improve their listings and travelers make informed decisions.

## Notebooks

- **Airbnb Listing Analysis.ipynb**: The Jupyter notebook contains the full analysis, from data cleaning to insights. It includes detailed explanations, code snippets, and visualizations to illustrate each step.

## Visualizations

The project includes several data visualizations:

- **Average Listing Price by Paris Neighborhood**: Shows the average listing price for different neighborhoods in Paris, providing insights into how location affects pricing.

<img width="600" alt="Average Listing Price by Price Neighbourhood" src="Graphical Interpretations/Average Listing Price by Price Neighbourhood.png">

- **Average Listing Price by Accommodates Number**: Illustrates how the average price changes depending on the number of people a listing can accommodate, helping to identify optimal pricing strategies based on capacity.

<img width="600" alt="Average Listing Price by Accommodates Number" src="Graphical Interpretations/Average Listing Price by Accommodates Number.png">

- **New Airbnb Hosts in Paris Over Time**: Displays the trend of new Airbnb hosts joining over time, giving insights into the growth of the Airbnb market in Paris.

<img width="600" alt="New AirBnB Hosts in Paris Over Time" src="Graphical Interpretations/New AirBnB Hosts in Paris over Time.png">

- **Average Airbnb Price in Paris Over Time**: Tracks changes in the average listing price over time, helping to identify pricing trends and seasonality.

<img width="600" alt="Average AirBnB Price in Paris Over Time" src="Graphical Interpretations/Average AirBnB Price in Paris Over Time.png">

- **Dual Axis Line Chart of Average Price and New Hosts Over Time**: Combines the trends of average price and new host additions over time, providing a comprehensive view of market dynamics.

<img width="600" alt="Dual Line Graph" src="Graphical Interpretations/Dual Line Graph.png">


These visualizations provide a clear understanding of the factors that influence Airbnb listing performance and how different attributes vary across locations and over time.

## Getting Started

To get started with this project:

1. Clone the repository to your local machine.
   ```bash
   git clone https://github.com/yourusername/airbnb-listing-analysis.git
   ```
2. Ensure you have all the necessary Python libraries installed. You can install them using:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook (`Airbnb Listing Analysis.ipynb`) to explore the data and run the analysis.

## Project Structure

- **Listings.csv**: The dataset used for analysis.
- **Airbnb Listing Analysis.ipynb**: Jupyter Notebook containing the entire analysis.
- **README.md**: Project overview and documentation (this file).
- **requirements.txt**: List of dependencies to install.

## Future Improvements

- **Additional Data Sources**: Incorporate other data sources, such as customer reviews or seasonal data, to enhance analysis.
- **Interactive Maps**: Utilize interactive maps to visualize Airbnb listings by location, price, and availability.
- **Dashboard Development**: Create an interactive dashboard using tools like Tableau or Power BI to provide real-time insights into Airbnb listings.

## Conclusion

The Airbnb Listing Analysis project provides valuable insights into the factors influencing Airbnb listing performance in Paris. Key determinants such as neighborhood, room type, and number of reviews play a significant role in determining listing prices and booking rates. By understanding these factors, hosts can optimize their listings to maximize revenue, while travelers can make informed decisions when booking accommodations. The visualizations and analysis in this project highlight the importance of location, amenities, and property types in shaping the short-term rental market, offering actionable insights for both hosts and guests.

## Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request if you have any suggestions for improving the project.


## Contact

For questions or suggestions, please contact [Kaushik Rohida](mailto:rohidakaushik@gmail.com).
