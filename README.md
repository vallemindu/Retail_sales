This project performs data preprocessing, cleaning, and exploratory data analysis (EDA) on a retail sales dataset. 
The dataset contains information such as product sales, prices, order dates, discounts, taxes, and more.

📋 About the Project

The objective of this project is to:
- Clean and preprocess raw retail data.
- Handle missing values and date conversions.
- Normalize features and remove outliers.
- Perform exploratory data analysis with meaningful visualizations.
- Prepare data for further analysis or machine learning use cases.

⚙️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn


✅ Project Features

- 🧼 Data cleaning and preprocessing
  - Missing value handling (`Color`, `ListPrice`, `SalesRegion`, `OrderQuantity`)
  - Date format conversion for `Orderdate`, `Duedate`, `Shipdate`
- 📈 Outlier removal using z-score method on `SalesAmount`
- 📊 Visualization of:
  - Boxplots for price across categories
  - Histograms for numeric distributions
- 📐 Feature normalization (z-score on `ListPrice`)


💻 Installation
Clone this repo
   ```bash
   git clone https://github.com/yourusername/retail-data-analysis.git
   cd retail-data-analysis
