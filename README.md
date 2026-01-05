# Final-Year-Project
This is my first Project

# Heart Attack Risk Prediction Using Clinical and Biochemical Indicators

This project focuses on predicting the risk of heart attack using clinical and biochemical data, such as:
- Age
- Gender
- Blood pressure
- Glucose level
- CK-MB enzyme
- Troponin level

The goal is to preprocess the dataset, perform exploratory data analysis (EDA), and prepare the data for machine learning classification models.

## **Libraries Used**
- **pandas** for data manipulation
- **numpy** for numerical operations
- **matplotlib** and **seaborn** for data visualization
- **scikit-learn** for machine learning tools such as MinMaxScaler, LabelEncoder, and train-test split functions
- **scipy** for statistical functions

## **Dataset**
- **Name:** Heart Attack Data
- **Source:** Collected from clinical sources and normalized

## **Steps Performed in the Notebook**
1. **Importing Required Libraries:** The necessary libraries for data manipulation, visualization, and machine learning are imported.
2. **Loading the Dataset:** The dataset is loaded from an Excel file, and the structure of the dataset is previewed.
3. **Exploratory Data Analysis (EDA):** Basic statistics and visualizations are performed to understand the dataset and the relationships between features.
4. **Handle Missing Values:** Missing values are identified and imputed using the mean strategy for numerical features.
5. **Data Preprocessing:** The dataset is scaled, and features are prepared for model training. The dataset is split into training and testing sets.
6. **Model Training and Evaluation:** Machine learning models are trained and evaluated based on classification accuracy, precision, recall, and F1-score.

## **How to Run the Notebook**
1. Clone the repository to your local machine.
2. Ensure you have the required Python libraries installed by running:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn scipy
   ```
3. Download the dataset (Heart attack data) and upload it in the appropriate location or use the dataset from the provided source.
4. Open the notebook in Jupyter Notebook or Google Colab.
5. Execute all the cells to perform data analysis and model training.

## **Results**
The goal of this project is to predict heart attack risk using machine learning models and to analyze the factors that contribute to the risk.

## **Contributions**
Feel free to contribute by:
- Improving model performance.
- Adding new machine learning algorithms.
- Enhancing data preprocessing techniques.

## **License**
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
