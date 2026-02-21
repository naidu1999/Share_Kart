# Share_Kart
# 📈 SuperKart Sales Forecasting & Deployment Project

## 📖 Project Overview

Accurate sales forecasting is critical for retail organizations to plan inventory, optimize supply chains, and make informed business decisions. By predicting future sales, companies can reduce risks related to overstocking or stockouts, improve regional sales planning, and establish performance benchmarks.

**SuperKart** is a retail chain operating supermarkets and food marts across multiple tier cities. Due to variations in product demand, store size, location, and customer behavior, SuperKart requires a reliable forecasting system to predict **sales revenue for the upcoming quarter** across its outlets.

In this project, I worked as a **Data Scientist** to analyze historical sales data, build a predictive model, and develop a **deployable sales forecasting solution** that can be integrated into SuperKart’s decision-making systems.

---

## 🎯 Business Objective

The objectives of this project are:

- Forecast product-level sales revenue across SuperKart stores
- Help optimize inventory planning and procurement
- Support regional and store-level sales strategy decisions
- Build a scalable forecasting solution ready for deployment
- Enable business teams to access predictions via a frontend interface

---

## 🗂 Dataset Description

The dataset contains historical sales data capturing both **product-related** and **store-related** attributes.

Each row represents the **total sales revenue of a specific product in a specific store**.

---

## 📘 Data Dictionary

| Feature | Description |
|------|------------|
| Product_Id | Unique identifier for each product |
| Product_Weight | Weight of the product |
| Product_Sugar_Content | Sugar category (low, regular, no sugar) |
| Product_Allocated_Area | Display area ratio of the product |
| Product_Type | Product category (meat, dairy, snacks, beverages, etc.) |
| Product_MRP | Maximum retail price |
| Store_Id | Unique identifier for each store |
| Store_Establishment_Year | Year the store was established |
| Store_Size | Store size (Low, Medium, High) |
| Store_Location_City_Type | City tier (Tier 1, Tier 2, Tier 3) |
| Store_Type | Type of store (Supermarket, Food Mart, etc.) |
| Product_Store_Sales_Total | Target variable – total sales revenue |

---

## 🛠 Tools & Technologies Used

- **Programming Language:** Python  
- **Environment:** Google Colab / Jupyter Notebook  
- **Libraries Used:**
  - pandas, numpy – data manipulation
  - matplotlib, seaborn – visualization
  - scikit-learn – modeling & evaluation
- **Deployment:**
  - Hugging Face Spaces (Frontend & Backend)

---

## 🔍 Project Workflow & Work Done

The project was executed following an end-to-end data science lifecycle.

---

### 1️⃣ Data Understanding & Exploration

- Loaded and inspected the dataset
- Checked data types, missing values, and distributions
- Generated summary statistics
- Understood relationships between product, store, and sales variables

---

### 2️⃣ Exploratory Data Analysis (EDA)

EDA was performed to uncover patterns influencing sales:

- Sales variation across product categories
- Impact of store size and location tier on revenue
- Relationship between product price (MRP) and sales
- Influence of store age and store type on performance

Visualizations such as **bar plots, box plots, and distribution plots** were used to support insights.

---

### 3️⃣ Data Preprocessing

- Handled missing values and inconsistencies
- Encoded categorical variables
- Created meaningful features from existing data
- Split the dataset into training and testing sets

---

### 4️⃣ Model Building

- Built regression-based predictive models to forecast sales revenue
- Compared model performance using suitable evaluation metrics
- Tuned hyperparameters to improve prediction accuracy

---

### 5️⃣ Model Evaluation

Models were evaluated using:
- RMSE / MAE
- R² score
- Error analysis across different store and product segments

The best-performing model was selected for deployment.

---

## 🚀 Deployment

To operationalize the solution:

- Deployed the trained model using **Hugging Face Spaces**
- Built a **backend API** for prediction
- Developed a **frontend interface** allowing users to input product and store details
- Enabled real-time sales forecasting for business users

🔗 **Hugging Face Spaces Links:**  
- Frontend: *(Added in notebook)*  
- Backend: *(Added in notebook)*  

---

## 📊 Key Insights

- Store size and location tier strongly influence sales revenue
- Certain product categories consistently outperform others
- Product pricing and allocated shelf space significantly impact sales
- Older and well-established stores tend to generate higher revenue

---

## 💡 Business Recommendations

- Optimize inventory for high-performing product categories
- Adjust procurement strategies based on regional demand forecasts
- Improve shelf allocation for high-impact products
- Use forecast outputs to plan quarterly sales targets and promotions

---

## 📁 Repository Structure
SuperKart-Sales-Forecasting/
│
├── SuperKart_Sales_Forecast.ipynb
├── SuperKart_Sales_Forecast.html
└── README.md

---

## 📌 Conclusion

This project demonstrates how **data-driven sales forecasting** can support strategic decision-making in retail. By combining historical data analysis, predictive modeling, and deployment, the solution enables SuperKart to forecast sales accurately and plan operations efficiently.

The project delivers a **scalable, deployable forecasting system** that bridges analytics and real-world business use.

---

## 👤 Author

**Rahul Naidu**  
B.Tech – Computer Science (2022)  
Aspiring Data Scientist / Business Analyst  

---

⭐ If you find this project useful, feel free to star the repository!
