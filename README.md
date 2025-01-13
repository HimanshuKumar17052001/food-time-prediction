# Food Delivery Time Prediction

## Overview
This project focuses on predicting food delivery times based on historical data and various influencing factors. The repository includes a Jupyter notebook and dataset to analyze, preprocess, and build predictive models to estimate delivery times.

## Features
- Exploratory Data Analysis (EDA) to understand key insights.
- Data preprocessing and feature engineering.
- Machine learning models for delivery time prediction.
- Evaluation metrics to assess model performance.

## Project Structure
```
📁 Food-Delivery-Time-Prediction
├── food-delivery-time-prediction.ipynb  # Jupyter notebook for analysis and modeling
├── dataset.csv  # Dataset
├── README.md  # Project documentation
└── requirements.txt  # Dependencies for the project
```

## Getting Started

### Prerequisites
- Python 3.8 or above
- Jupyter Notebook
- Recommended: Virtual environment (e.g., `venv`, `conda`)

### Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Food-Delivery-Time-Prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Food-Delivery-Time-Prediction
   ```
3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Notebook
1. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Open the file `food-delivery-time-prediction.ipynb` and run the cells sequentially.

## Dataset
The dataset (`dataset.csv`) includes detailed information about food delivery orders and their associated attributes:

### Order Details
- **ID**: Unique identifier for each order.
- **Type_of_order**: The category of the order (e.g., meal, beverage, dessert).

### Delivery Personnel Information
- **Delivery_person_ID**: Unique identifier for the delivery personnel.
- **Delivery_person_Age**: Age of the delivery personnel.
- **Delivery_person_Ratings**: Customer ratings of the delivery personnel.

### Location Information
- **Restaurant_latitude**, **Restaurant_longitude**: Geographical coordinates of the restaurant.
- **Delivery_location_latitude**, **Delivery_location_longitude**: Geographical coordinates of the delivery location.
- **Delivery Distance**: The distance between the restaurant and the delivery location.

### Delivery Vehicle Details
- **Type_of_vehicle**: The type of vehicle used for the delivery.

### Environmental Factors
- **Weather Conditions**: Weather details during delivery (not directly listed but relevant to time taken).

### Target Variable
- **Time_taken(min)**: The delivery time in minutes, which is the target variable.

This dataset is useful for analyzing factors affecting delivery time and optimizing delivery operations.


## Model Building
1. Preprocessing: Handling missing values, feature scaling, and encoding categorical data.
2. Exploratory Data Analysis: Insights into the factors affecting delivery times.
3. Model Selection: Multiple models, including:
   - Linear Regression
   - Random Forest
   - Gradient Boosting
4. Evaluation: Metrics used include Mean Absolute Error (MAE), Mean Squared Error (MSE), and R².

## Results
Summarize key findings, including:
- Best-performing model.
- Accuracy metrics.
- Key factors influencing delivery time.

## Future Work
- Incorporate real-time data.
- Experiment with additional advanced models.
- Optimize for deployment-ready pipelines.

## Contributions
Contributions are welcome! Feel free to open issues or submit pull requests for improvements.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact
For any inquiries or issues, feel free to reach out:
- **Your Name**: [himanshu.kumar0012@gmail.com](himanshu.kumar0012@gmail.com)
- **GitHub**: [HimanshuKumar17052001](https://github.com/HimanshuKumar17052001)
