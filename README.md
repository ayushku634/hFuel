# hFuel Text Analysis Project

## Overview
The hFuel Text Analysis Project focuses on analyzing social media data from both developing and developed countries. The project employs various machine learning models to predict total interactions based on different features extracted from the data.

## Data
The project utilizes datasets from Facebook pages of both developing and developed countries. The data includes various metrics such as post types, likes, shares, comments, and other interaction-related features. Additionally, topic distributions and valence scores are included to enrich the dataset.

### Datasets
- **Developing Countries Dataset:** Contains data specific to social media pages from developing nations, including interaction metrics and topic distributions.
- **Developed Countries Dataset:** Comprises similar metrics but from developed nations, allowing for comparative analysis.

## Approach
The project follows a systematic approach to analyze and model the data:

1. **Data Preprocessing:**
   - **Data Cleaning:** Removal of irrelevant columns and handling of missing values.
   - **Feature Engineering:** Creation of new features such as post type indicators (e.g., IsVideo, IsPhoto).
   - **Standardization:** Scaling numerical features to ensure uniformity across the dataset.

2. **Modeling:**
   - **Train-Test Split:** Dividing the dataset into training and testing subsets to evaluate model performance.
   - **Machine Learning Models:**
     - **XGBoost:** An ensemble learning method based on decision trees.
     - **Random Forest:** Another ensemble method that builds multiple decision trees.
     - **Support Vector Regression (SVR):** A regression technique based on support vector machines.
     - **Poisson Regression:** Suitable for count-based dependent variables.

3. **Evaluation:**
   - **Metrics Used:** Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² Score.
   - **Best Model Selection:** Determination of the best-performing model based on the evaluation metrics.

4. **Visualization:**
   - **Feature Importance:** Analysis of which features contribute most to the model's predictions.
   - **Partial Dependence Plots:** Understanding the relationship between features and the target variable.
   - **Correlation Matrix:** Visual representation of feature correlations to identify multicollinearity.

## Functionalities
The project is divided into several Jupyter notebooks, each responsible for different aspects of the analysis:

### Text Analysis
- **Developing_Countries.ipynb:** [Description of functionalities once available]
- **Developed_Countries.ipynb:** [Description of functionalities once available]

### Applying ML Models on the Dataset
- **Developing_Countries_ML.ipynb:** [Description of functionalities once available]
- **Developed_Countries_ML.ipynb:**
  - **Data Import and Cleaning:** Loading datasets, installing necessary libraries, and cleaning data by removing irrelevant columns.
  - **Feature Engineering:** Creating binary indicators for different post types and handling topic distributions.
  - **Model Training:** Implementing XGBoost, Random Forest, SVR, and Poisson Regression models.
  - **Model Evaluation:** Calculating MSE, RMSE, and R² scores for in-sample and out-sample predictions.
  - **Best Model Selection:** Identifying the best predictive model based on multiple metrics.
  - **Visualization:** Generating feature importance scores and partial dependence plots for the best model.
  - **Correlation Analysis:** Creating and visualizing correlation matrices to assess feature relationships.

## Usage
To replicate the analysis:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/hFuel.git
   ```

2. **Navigate to the Project Directory:**
   ```bash
   cd hFuel
   ```

3. **Install Required Libraries:**
   Ensure you have Python 3 installed. Install dependencies using:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Notebooks:**
   Open the Jupyter notebooks and run them sequentially to perform the analysis.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue to discuss changes.

## License
This project is licensed under the MIT License.
