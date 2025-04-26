# Cars-Performance-Analysis_using_Pyspark

This project analyzes car performance data from the **Auto MPG dataset** using **PySpark**.  
It focuses on exploring relationships between different car attributes such as horsepower, weight, fuel efficiency, and acceleration to derive meaningful insights.

## Project Structure

- `auto-mpg.csv` — Dataset containing car specifications and performance metrics.
- `CarsPerformanceAnalysis_using_Pyspark.ipynb` — Jupyter Notebook for data cleaning, exploration, and analysis using PySpark.

## Features

- **Data Cleaning**: Handling missing values and correcting data types.
- **Feature Engineering**: Creating new meaningful attributes from the existing dataset.
- **Exploratory Data Analysis (EDA)**: Using PySpark SQL and DataFrame operations to generate insights.
- **Visualization**: Visual graphs and charts for better understanding.
- **Performance Insights**: Analyzing how different factors like weight, horsepower, and cylinders affect miles per gallon (MPG).

## Technologies Used

- Python 3.x
- PySpark
- Pandas 
- Jupyter Notebook

## Setup Instructions

1. **Clone the Repository**  
```bash
git clone https://github.com/Pardhasai7/Cars-Performance-Analysis_using_Pyspark.git
cd Cars-Performance-Analysis_using_Pyspark
```

2. **Install Dependencies**  
Make sure you have `pyspark` installed. If not, install it using:
```bash
pip install pyspark
```

3. **Run the Notebook**  
Launch Jupyter Notebook and open `CarsPerformanceAnalysis_using_Pyspark.ipynb`.

```bash
jupyter notebook
```

4. **Dataset**  
Ensure that `auto-mpg.csv` is in the same directory as the notebook or adjust the dataset path accordingly.

## Dataset Information

The **Auto MPG dataset** includes the following fields:

- `mpg`: Miles per gallon
- `cylinders`: Number of cylinders
- `displacement`: Engine displacement (cu inches)
- `horsepower`: Engine horsepower
- `weight`: Vehicle weight (lbs)
- `acceleration`: Time to accelerate from 0 to 60 mph (sec)
- `model_year`: Year of the car model
- `origin`: Origin of the car (1: USA, 2: Europe, 3: Asia)
- `car_name`: Name of the car

(Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/auto+mpg))

## License

This project is open-source and available under the [MIT License](LICENSE).
