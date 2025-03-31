# Customer Insights Using Data Analysis and Forecasting

## Project Overview

This project focuses on analyzing customer transaction data to derive meaningful insights for business strategy and decision-making. It utilizes various data analysis techniques such as Exploratory Data Analysis (EDA), feature selection, customer segmentation using K-means clustering, and classification models for predicting customer behavior.

### Key Objectives:
1. **Exploratory Data Analysis (EDA)**: Understanding data patterns, distributions, and key factors affecting customer behavior.
2. **Feature Selection**: Identifying the most relevant features to improve model performance.
3. **Customer Segmentation**: Using K-means clustering to segment customers into distinct groups based on transaction history and other key features.
4. **Classification Models**: Building and evaluating classification models to predict customer behavior and make data-driven decisions.
5. **Precision Comparison**: Comparing the precision of multiple classification models to select the best-performing model.

## Libraries Used

The following Python libraries are used for data analysis, machine learning, and visualization:

- **pandas**: For data manipulation and analysis.
- **numpy**: For numerical computations.
- **matplotlib** and **seaborn**: For data visualization.
- **scikit-learn**: For machine learning models and preprocessing.
- **KMeans**: For clustering and customer segmentation.
- **train_test_split**: For splitting data into training and testing sets.
- **metrics**: For calculating model precision, recall, and accuracy.

## Data Overview

The dataset contains information about customer transactions, including various demographic features (e.g., age, gender, income) and transaction data (e.g., purchase frequency, spending patterns). The data is used to:

1. Perform **Exploratory Data Analysis** to identify trends.
2. Select the most important features using statistical methods.
3. Segment customers into meaningful groups using **K-means clustering**.
4. Build classification models to predict customer behavior.
5. Evaluate the models based on their precision and accuracy.

## Steps Involved

### 1. Exploratory Data Analysis (EDA)
   - Loading and inspecting the dataset.
   - Visualizing key distributions and relationships in the data.
   - Identifying missing values and handling them appropriately.

### 2. Feature Selection
   - Using statistical methods (e.g., correlation analysis, feature importance) to select the most relevant features.
   - Removing irrelevant or redundant features to improve model performance.

### 3. Customer Segmentation with K-means Clustering
   - Normalizing data and applying the K-means clustering algorithm to segment customers into distinct groups based on their transactional behavior.
   - Analyzing and visualizing the clusters to understand customer segments.

### 4. Building Classification Models
   - Splitting the data into training and testing sets.
   - Training several classification models (e.g., Logistic Regression, Random Forest, Support Vector Machine).
   - Tuning model hyperparameters to improve performance.

### 5. Precision Comparison
   - Comparing model performance using metrics such as precision, recall, F1-score, and accuracy.
   - Selecting the best model based on the precision scores and validating its results on test data.

## Results

The project demonstrates the following results:
- Insights into customer behavior and purchasing trends through EDA.
- Identification of key features influencing customer behavior.
- Clear customer segments using K-means clustering.
- An evaluation of several classification models with precision comparison, leading to a selection of the best-performing model for predicting customer behavior.

## How to Run the Code

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/customer-insights.git
2. **Install Dependencies: Install the required libraries listed in the requirements.txt file using the following command**
   ```bash
   pip install -r requirements.txt
3. **Run the Scripts: Once the dependencies are installed, you can start running the scripts:**

- **For Exploratory Data Analysis (EDA):**

To run the EDA scripts, execute the following commands:

1. Run the EDA script:
   ```bash
   python eda.py
2. Run the Lookalike Model script:
   ```bash
   python lookalikemodel.py
3. Run the Clustering script in Command Prompt:
   ```bash
   code .
   python main.py
