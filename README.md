# Flight-Price-Prediction
This project predicts flight ticket prices using machine learning. It involves data cleaning, EDA, and building regression models like Linear Regression, Random Forest, and XGBoost. Technologies: Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, and Jupyter Notebook.
---

## Dataset
**Dataset Source:** [Kaggle: Flight Price Prediction](https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction?resource=download)

### Dataset Features:
- **Airline**: The airline providing the service.
- **Date of Journey**: Date of the flight.
- **Source**: The starting location of the flight.
- **Destination**: The flight destination.
- **Route**: The route taken by the flight.
- **Duration**: Total travel time.
- **Total Stops**: Number of stops on the flight.
- **Price**: The target variable (flight ticket price).

---

## Objectives
1. **Data Cleaning**: Handle missing values, format inconsistencies, and outliers.
2. **Feature Engineering**:
   - Extract meaningful features from date and duration columns.
   - Encode categorical variables.
3. **Exploratory Data Analysis (EDA)**: Identify trends and correlations to understand the factors affecting flight prices.
4. **Model Building**:
   - Use regression techniques to predict ticket prices.
   - Compare models like Linear Regression, Random Forest, and XGBoost.
5. **Model Evaluation**: Use metrics like RMSE and MAE to evaluate model performance.
6. **Visualization**: Create visualizations to present insights and results.

---

## Project Workflow
1. **Data Loading**
    - Load the dataset and inspect its structure.
2. **Data Cleaning**
    - Handle missing or inconsistent data.
    - Format columns (e.g., convert duration to numerical values).
3. **EDA**
    - Visualize distributions and relationships.
    - Identify outliers and correlations.
4. **Feature Engineering**
    - Encode categorical variables.
    - Extract date and time features.
    - Normalize/scale numerical variables if needed.
5. **Model Building**
    - Split the dataset into training and testing sets.
    - Train models and tune hyperparameters.
    - Evaluate performance on the test set.
6. **Results and Visualization**
    - Present model performance.
    - Create visualizations for insights and predicted vs. actual prices.
7. **Documentation**
    - Summarize the project in this README and in a Jupyter notebook.

---

## Repository Structure
```
Flight-Price-Prediction/
├── data/               # Raw and cleaned datasets
├── notebooks/          # Jupyter notebooks
├── src/                # Scripts for cleaning, modeling, etc.
├── outputs/            # Visualizations, predictions
├── README.md           # Project overview
└── requirements.txt    # Dependencies (e.g., pandas, scikit-learn)
```

---

## Installation and Setup
1. Clone this repository:
   ```bash
   git clone <repository_url>
   ```
2. Navigate to the project directory:
   ```bash
   cd Flight-Price-Prediction
   ```
3. Install required packages:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter notebook to see the workflow or execute scripts in the `src/` directory.

---

## Results
- **Best Model:** (To be filled after model evaluation)
- **Performance Metrics:** RMSE: XX, MAE: XX

---

## Future Enhancements
- Deploy the model using Flask or Streamlit for real-time predictions.
- Experiment with deep learning techniques for further improvement.
- Integrate more features like weather conditions or booking time to enhance predictions.

---

## Contributing
Feel free to submit issues or pull requests to improve this project. Collaboration is welcome!

---

## License
This project is licensed under the MIT License.
