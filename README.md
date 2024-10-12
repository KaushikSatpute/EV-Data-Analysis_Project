# Exploratory Data Analysis on Electric Vehicle Dataset
This project involves performing an in-depth Exploratory Data Analysis (EDA) on an Electric Vehicle (EV) dataset to gain insights into the adoption and distribution of electric vehicles across different regions, years, and manufacturers. The analysis aims to provide a comprehensive understanding of EV trends, popular makes and models, and other factors influencing electric vehicle growth.

Project Overview
The project explores key aspects of electric vehicle data, including:

Distribution of Electric Vehicle Types: Analyzing the frequency and distribution of different EV types.
EV Makes Over the Years: Examining the popular makes and manufacturers over time with a racing bar plot visualization.
Geographical Analysis: Exploring the geographic distribution of electric vehicles.
Trend Analysis: Identifying trends in EV adoption over the years.
Correlation Analysis: Investigating relationships between variables such as model year, vehicle type, and manufacturer.
Dataset
The dataset used for this project includes information on electric vehicles, covering fields such as:

Model Year: The year the EV model was manufactured.
Make: The manufacturer of the electric vehicle.
Electric Vehicle Type: The type of EV (e.g., Battery Electric Vehicle, Plug-in Hybrid, etc.).
County and State: The geographic location where the EV is registered.
Note: The dataset should be loaded as a CSV file named electric_vehicle_data.csv (or another appropriate name based on your file).

Tools and Libraries
The project utilizes the following Python libraries:

Pandas for data manipulation and cleaning
NumPy for numerical operations
Matplotlib and Seaborn for data visualization
Plotly for creating interactive plots, such as animated bar charts
Jupyter Notebook for code and visualization execution
Analysis Workflow
The project follows these key steps:

Data Cleaning: Checking for missing values, duplicates, and correcting data types.
Data Exploration: Generating summary statistics and visualizing distributions.
Visualizations: Creating plots to explore trends and distributions, including:
Count plots for EV types and manufacturers.
Animated racing bar charts for visualizing EV makes over the years.
Geographic plots to analyze EV distribution by region.
Insights and Conclusions: Summarizing the findings and key insights derived from the analysis.
Visualizations
Sample Plots
Electric Vehicle Types Distribution: Shows the distribution of different types of EVs.
Racing Bar Chart of EV Makes Over the Years: An animated visualization of popular EV makes by year.
Geographic Distribution: Maps showing the regional distribution of electric vehicles.
Getting Started
Clone the Repository:

bash
Copy code
git clone https://github.com/yourusername/ev-eda.git
cd ev-eda
Install Dependencies:

bash
Copy code
pip install -r requirements.txt
Run the Notebook: Open the Jupyter notebook file (ev_eda.ipynb) and run the cells to perform the analysis.

Future Enhancements
Potential future enhancements include:

Integrating additional data sources to explore external factors influencing EV adoption.
Conducting predictive analysis on EV trends.
Developing interactive dashboards for real-time data exploration.
Contributing
Contributions are welcome! If you would like to contribute to this project, please fork the repository and submit a pull request.
