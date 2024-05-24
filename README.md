# Customer Segmentation with K-Means Clustering

This project aims to segment customers based on their annual income and spending score data using the K-Means clustering algorithm. By grouping customers into distinct clusters, businesses can better understand their customer base and develop targeted marketing strategies.

## Dataset

The project uses a customer dataset that includes various features such as age, income, spending scores, and purchase history. The dataset is in CSV format and can be found in the `data` directory.

## Requirements

- Python 3.6 or later
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## Usage

1. Clone the repository:

```
git clone https://github.com/MdZaid27/customer-segmentation.git
```

2. Navigate to the project directory:

```
cd customer-segmentation
```

3. Install the required dependencies:

```
```

4. Run the Jupyter Notebook:

```
jupyter notebook
```

This will open the Jupyter Notebook interface in your default web browser.

5. Open the `Customer Segmentation.ipynb` notebook and follow the instructions provided.

## Project Structure

```
customer-segmentation/
├── Customer Segmentation.ipynb # Jupyter Notebook containing the code
├── data/
│   └── customers.csv # Customer dataset
├── README.md
```

## Methodology

The project follows these steps:

1. **Data Collection**: Load the customer dataset from the CSV file.
2. **Exploratory Data Analysis**: Analyze the dataset to understand its characteristics and identify any potential issues.
3. **Data Preprocessing**: Handle missing values, encode categorical variables, and standardize the feature data.
4. **Determining the Optimal Number of Clusters**: Use the Elbow method to determine the optimal number of clusters.
5. **K-Means Clustering**: Apply the K-Means algorithm to segment customers into clusters.
6. **Cluster Analysis**: Analyze the characteristics of each cluster and interpret the results.
7. **Visualization**: Visualize the clusters using scatter plots and other relevant visualizations.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
