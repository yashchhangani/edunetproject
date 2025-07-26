
# City Reservoir Level Prediction 📉

This project uses **Linear Regression** to predict City reservoir levels based on historical data. It includes data cleaning, correlation analysis, model training, evaluation, and visualizations.

## 📁 Project Structure

```
reservoir-level-prediction/
├── data/
│   └── city_reservoir_levels.xlsx     # Dataset
├── reservoir_prediction.py            # Main ML script
├── README.md                          # Project description
└── .gitignore                         # (Optional) Ignore temp files
```

## 📊 Features

- Loads `.xlsx` dataset using `pandas`
- Drops missing and non-numeric values
- Correlation heatmap to analyze feature relationships
- Linear regression using `scikit-learn`
- Evaluation: Mean Squared Error and R² Score
- Visualizations:
  - Actual vs Predicted scatter plot
  - Residuals histogram

## 📦 Requirements

Install the following Python libraries before running the script:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn openpyxl
```

## 🚀 How to Run

1. Clone the repository or download the files.
2. Ensure the dataset is located at: `data/city_reservoir_levels.xlsx`
3. Run the Python script:

```bash
python reservoir_prediction.py
```

## 📈 Output Visualizations

The script will generate:
- ✅ Correlation Heatmap
- ✅ Actual vs Predicted Plot
- ✅ Residual Distribution Histogram

These plots help you understand model performance and error behavior.

## 📌 Notes

- The dataset should be in Excel (`.xlsx`) format.
- The script assumes all numeric features except the target are inputs (`X`).
- Uses 80/20 train-test split.

## 👤 Author

**Your Name**  
GitHub: [@your_username](https://github.com/your_username)

## 📄 License

This project is open-source and free to use for educational or research purposes.
