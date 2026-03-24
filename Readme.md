# 🍕 Pizza Sales Analysis Project

📌 Project Overview:-

This project provides a comprehensive exploratory data analysis (EDA) of pizza sales records to identify trends, popular products, and revenue drivers. Using Python-based data science libraries, the analysis explores customer preferences across different pizza categories, sizes, and ingredients.

🛠️ Technologies Used

The following Python libraries were utilized for data manipulation, analysis, and visualization:
Data Handling: pandas, numpy
Visualization: matplotlib, seaborn, plotly
Text Analysis: wordcloud

📊 Dataset Description

The dataset consists of 48,620 entries with 12 distinct columns:
Order Details: order_id, order_date, order_time, quantity.
Product Information: pizza_name, pizza_category, pizza_size, pizza_ingredients.
Pricing: unit_price, total_price.

🔍 Key Analysis Steps

Data Loading: Importing the dataset from CSV format for processing.
Exploratory Data Analysis (EDA):
Inspecting data types and missing values using .info().
Statistical summary of numerical columns (price, quantity) using .describe().

Visualizations:

Distribution of sales across different pizza sizes (S, M, L, XL, XXL).
Revenue analysis by pizza category (Classic, Veggie, Supreme, Chicken).
Ingredient frequency analysis using Word Clouds.
The Pizza Sales Analysis Project utilizes several Python libraries and tools for data processing, analysis, and visualization.

Core Libraries

NumPy: Used for linear algebra and numerical operations.
Pandas: The primary tool for data processing and managing CSV file I/O.
Seaborn: Employed for statistical data visualization.
Matplotlib (pyplot): Used for creating static and basic visualizations, often with specific styles like Solarize_Light2.
Plotly (graph_objs and express): Used for generating interactive plots and complex visualizations.
WordCloud: Specifically used for generating word clouds, often to visualize text data like pizza ingredients.

🚀 How to Run the Project

1. Clone this repository:
Bash
git clone https://github.com/your-username/pizza-sales-analysis.git

2. Install the required dependencies:
Bash
pip install pandas numpy matplotlib seaborn plotly wordcloud

3. Open and run the Jupyter Notebook:
Bash
jupyter notebook "Pizza Sales Analysis Project.ipynb"

📈 Key Insights (Sample)

Average Order Value: The mean total price per order item is approximately $16.82.
Popular Sizes: The analysis tracks sales across five sizes, ranging from Small (S) to Extra-Extra-Large (XXL).
Variety: The menu features 32 unique pizza names across 4 major categories.
