# Big Basket Analysis  🚀

## 📊 Overview
This project presents an analysis of a Big Basket product dataset containing 10 attributes. The analysis explores key insights, performs data cleaning, and visualizes trends using Python.

### 🗃️ Dataset Description
The dataset consists of the following attributes:
- **index**: Serial number of the record
- **product**: Name of the product
- **category**: Category under which the product is listed
- **sub_category**: Subcategory under which the product is listed
- **brand**: Brand of the product
- **sale_price**: Price at which the product is sold
- **market_price**: Market price of the product
- **type**: Type classification of the product
- **rating**: Customer rating for the product
- **description**: Product description

## 🛠️ Libraries Used
- `NumPy`
- `Pandas`
- `Seaborn`
- `Matplotlib`

## 📈 Analysis Workflow
### 1️⃣ Load Dataset
- Imported the dataset and displayed the first 12 rows using `.head()`.

### 2️⃣ Explore Data
- Analyzed data structure and summary statistics using `.info()` and `.describe()`.

### 3️⃣ Top and Least Sold Products
- Identified the most and least sold products based on sales data.

### 4️⃣ Discount Analysis
- Measured discounts by comparing `sale_price` and `market_price`.

### 5️⃣ Missing Value Handling
- Detected and handled missing values appropriately.

### 6️⃣ Outlier Detection
- Identified and treated outliers using statistical methods, filling with mean values.

### 7️⃣ Visualizations
- Created insightful plots using `Matplotlib` and `Seaborn` to uncover trends and patterns.

## 🚀 How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/big-basket-analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd big-basket-analysis
   ```
3. Install dependencies:
   ```bash
   pip install numpy pandas matplotlib seaborn
   ```
4. Run the Jupyter notebook or Python script.

## 📊 Sample Visualizations
- 📊 Bar Charts showing top-selling products
- 📉 Line Charts depicting price vs. discount
- 📈 Scatter Plots highlighting outliers

## 🙌 Contributing
Contributions are welcome! Please feel free to fork the repository and submit pull requests.

## 📝 License
This project is licensed under the MIT License.
--

