## Dynamic Pricing Model Analysis and Prediction

### Overview
This project explores a dynamic pricing model using a dataset `dynamic_pricing.csv` to analyze and predict transportation costs based on historical data and real-time supply-demand metrics. The project utilizes Python with libraries such as Pandas, NumPy, Plotly, and scikit-learn for data manipulation, visualization, and machine learning.

### Dataset
The dataset `dynamic_pricing.csv` includes the following key columns:
- `Historical_Cost_of_Ride`: The previous cost of the ride.
- `Expected_Ride_Duration`: Expected duration of the ride in minutes.
- `Number_of_Riders`: Number of riders requesting the ride.
- `Number_of_Drivers`: Available drivers at the time.
- `Vehicle_Type`: Type of vehicle requested (Economy or Premium).

### Features
- Exploratory Data Analysis (EDA) with visualizations for cost distribution and correlations.
- Handling of missing data and outliers.
- Implementation of a dynamic pricing model based on supply-demand metrics.
- Regression analysis to predict the adjusted cost of rides.
- Evaluation of model performance with actual vs. predicted pricing.

### Setup and Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Install required Python libraries:
   ```bash
   pip install pandas numpy plotly scikit-learn
   ```

### Usage
To run the analysis and view the visualizations:
1. Ensure you have the dataset `dynamic_pricing.csv` in the same directory as your script.
2. Run the script using a Python interpreter:
   ```bash
   python dynamic_pricing_analysis.py
   ```

### Scripts and Functions
- `data_preprocessing_pipeline(data)`: Processes the input data by handling missing values, outliers, and encoding categorical variables.
- `predict_price(number_of_riders, number_of_drivers, vehicle_type, expected_ride_duration)`: Predicts the price of a ride given the input parameters.
- Visualization functions to display scatter plots, box plots, correlation matrices, and pie charts for insights into the data and results.

### Contributions
Contributions to this project are welcome! You can contribute in the following ways:
- Enhance the machine learning model or propose new models.
- Add more visualizations to better understand the data.
- Improve the data preprocessing pipeline.

### License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
