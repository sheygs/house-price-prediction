# House Price Prediction

This project implements house price prediction models using the Melbourne Housing Market dataset. It demonstrates core ML concepts by building predictive models for Melbourne real estate prices, progressing from basic decision trees to advanced ensemble methods like Random Forests. Thus, it serves as a practical introduction to ML workflows, emphasizing proper model validation, handling overfitting/underfitting, and applying ensemble techniques to improve prediction accuracy.

## Dataset Description

### Melbourne Housing Market Data

The project uses real Melbourne housing market data with comprehensive property information:

**Key Features:**

- **Rooms**: Number of bedrooms
- **Price**: Property sale price (target variable)
- **Distance**: Distance from Melbourne CBD (km)
- **Type**: Property type (house, unit, townhouse)
- **Method**: Sale method (auction, private, etc.)
- **Bathroom**: Number of bathrooms
- **Car**: Number of car spaces
- **Landsize**: Property land size (square meters)
- **Latitude/Longitude**: Geographic coordinates
- **Council Area**: Local government area
- **Region Name**: General region classification
- **Property Count**: Number of properties in the suburb

**Dataset Files:**

- `melb_data.csv`: Complete Melbourne housing dataset
- `train.csv`: Training subset for model development
- `test.csv`: Testing subset for final evaluation

## Machine Learning Concepts Covered

This project implements and demonstrates the following core ML concepts:

### 1. Decision Trees

- **Tree-based models** that make predictions through decision splits
- Understanding feature importance and tree visualization
- Handling both numerical and categorical variables

### 2. Model Validation

- **Train-test splitting** for unbiased performance evaluation
- **Cross-validation techniques** for robust model assessment
- **Performance metrics** including Mean Absolute Error (MAE)

### 3. Overfitting and Underfitting

- **Model complexity optimization** through tree depth tuning
- **Bias-variance tradeoff** understanding
- **Regularization techniques** to prevent overfitting

### 4. Random Forests

- **Ensemble methods** combining multiple decision trees
- **Bootstrap aggregating** for improved predictions
- **Feature randomness** to reduce correlation between trees

### 5. Data Preprocessing

- **Handling missing values** through imputation or removal
- **Categorical variable encoding** using one-hot encoding
- **Feature selection** for optimal model performance

## 🔧 Technologies Used

- **Python 3.7+**: Core programming language
- **pandas**: Data manipulation and analysis
- **scikit-learn**: Machine learning algorithms and tools
- **NumPy**: Numerical computing support
- **Jupyter Notebook**: Interactive development environment

## 📦 Installation

### Prerequisites

- Python (>=3.7)
- pip package manager

### Installation Steps

1. **Clone the repository:**

```bash
git clone https://github.com/sheygs/house-price-prediction.git
cd house-price-prediction
```

2. **Create a virtual environment (recommended):**

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. **Install required packages:**

```bash
pip install pandas numpy scikit-learn
```

4. **Launch Jupyter Notebook:**

```bash
jupyter notebook house_price_prediction.ipynb
```

## How to Run the Project

### Interactive Notebook (Recommended)

1. Open `house_price_prediction.ipynb` in Jupyter Notebook
2. Run cells sequentially to follow the complete workflow
3. Experiment with different parameters and approaches
4. View model predictions in `output.csv`

### Expected Workflow:

1. **Data Loading**: Import Melbourne housing data using pandas
2. **Exploratory Analysis**: Understand dataset structure and patterns
3. **Data Preprocessing**: Handle missing values and encode categorical variables
4. **Model Building**: Implement decision tree and random forest models
5. **Model Validation**: Evaluate performance using proper validation techniques
6. **Prediction**: Generate house price predictions for test data
7. **Results Analysis**: Compare model performance and interpret outcomes

## 🪜 Project Structure

```
house-price-prediction/
│
├── datasets/
│   ├── melb_data.csv       # Complete Melbourne housing dataset
│   ├── train.csv           # Training data subset
│   └── test.csv            # Testing data subset
│
├── house_price_prediction.ipynb      # Main Jupyter notebook with complete analysis
├── output.csv                        # Model predictions and results
├── README.md                         # Project documentation
└── main.ipynb                        # Optional script version
```

## 💪 Acknowledgments

- **Kaggle** for providing the dataset
- **Melbourne Housing Market** data contributors
- The **scikit-learn** and **pandas** development communities
