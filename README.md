# Big_Mart_Sales_Prediction
Project aims to predict the sales of items in various Big Mart outlets using the XGBoost algorithm. The dataset includes several features related to the items and outlets, which are used to train and evaluate the model for accurate sales predictions.





This project aims to predict the sales of items in various Big Mart outlets using the XGBoost algorithm. The dataset includes several features related to the items and outlets, which are used to train and evaluate the model for accurate sales predictions.

## Dataset

The dataset consists of the following columns:
- `Item_Identifier`: Unique product ID
- `Item_Weight`: Weight of the product
- `Item_Fat_Content`: Fat content of the product (Low Fat, Regular)
- `Item_Visibility`: The percentage of total display area allocated to this product in the store
- `Item_Type`: The category to which the product belongs
- `Item_MRP`: Maximum Retail Price (list price) of the product
- `Outlet_Identifier`: Unique store ID
- `Outlet_Establishment_Year`: The year in which the store was established
- `Outlet_Size`: The size of the store (Small, Medium, High)
- `Outlet_Location_Type`: The location type of the store (Tier 1, Tier 2, Tier 3)
- `Outlet_Type`: The type of store (Grocery Store, Supermarket Type1, Type2, Type3)
- `Item_Outlet_Sales`: Sales of the product in the particular store (target variable)

## Project Structure

- `data/`: Directory containing the dataset.
- `notebooks/`: Jupyter notebooks used for data analysis, visualization, and model training.
- `src/`: Source code for data processing, model training, and evaluation.
- `models/`: Directory to save trained models.
- `README.md`: Project documentation.

## Getting Started

### Prerequisites

- Python 3.7+
- Required packages listed in `requirements.txt`

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/big-mart-sales-prediction.git
    cd big-mart-sales-prediction
    ```

2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

### Usage

1. Preprocess the data:
    ```sh
    python src/preprocess.py
    ```

2. Train the model:
    ```sh
    python src/train.py
    ```

3. Evaluate the model:
    ```sh
    python src/evaluate.py
    ```

### Example

You can find an example of the data preprocessing, training, and evaluation process in the Jupyter notebooks located in the `notebooks/` directory.

## Data Analysis and Visualization

The notebooks include detailed data analysis and visualization steps:
- Exploratory Data Analysis (EDA) to understand the distribution of features and their relationships.
- Visualization of key insights using plots and charts (e.g., histograms, bar plots, scatter plots).

## Results

The trained XGBoost model achieves an R² score of 0.5 on the test set. Detailed evaluation metrics and visualizations can be found in the `notebooks/` directory.

