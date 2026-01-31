# 🍔 Food Delivery Data Analysis Hackathon

This repository contains my submission for the **Innomatics Food Delivery Data Analysis Hackathon**.  
The objective of this hackathon was to integrate multiple data sources, create a unified dataset, and perform meaningful business analysis using Python.

---

## 📌 Problem Statement

The hackathon simulates a real-world food delivery platform where data is stored across different systems and formats:

- **orders.csv** – Transactional order-level data  
- **users.json** – User master data  
- **restaurants.sql** – Restaurant master data  

The task was to:

1. Combine all datasets into a single final dataset  
2. Perform exploratory data analysis  
3. Answer business-driven analytical questions  
4. Derive insights related to users, revenue, cuisine, and seasonality  

---

##  Dataset Description

### Input Files

| File Name | Description | Format |
|---------|-------------|--------|
| orders.csv | Order transactions | CSV |
| users.json | User information | JSON |
| restaurants.sql | Restaurant details | SQL |

---

### Final Dataset

After merging all sources using appropriate join keys:


The final dataset contains:

- Order details  
- User information  
- Restaurant attributes  
- Cuisine type  
- Ratings  
- Membership type  

---

##  Join Logic Used

| Source | Join Key |
|------|---------|
| orders → users | `user_id` |
| orders → restaurants | `restaurant_id` |

**Join type:**  


---

## 🛠️ Tools & Technologies

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SQLite
- Jupyter Notebook
- GitHub

---

## 📊 Analysis Performed

The following analyses were completed:

### ✅ Customer Analysis
- Total and distinct users
- Gold vs Regular membership behavior
- Order frequency per user

### ✅ Revenue Analysis
- City-wise revenue
- Cuisine-wise revenue
- Membership-based revenue contribution
- High-value users (₹1000+ spend)

### ✅ Cuisine & Restaurant Analysis
- Average order value by cuisine
- Restaurants with highest revenue
- High AOV restaurants with fewer orders
- Rating range vs revenue contribution

### ✅ Time Series & Seasonality
- Monthly order trends
- Quarterly revenue analysis
- Identification of peak revenue quarter

---

## 📈 Key Insights

- **Gold members** contribute significantly to overall revenue.
- **Mexican cuisine** shows high average order value despite fewer restaurants.
- **Chennai** generates the highest revenue among Gold members.
- **Q3 (Jul–Sep)** recorded the highest overall revenue.
- Restaurants rated between **4.1–4.5** generate maximum revenue.
- A small group of users contributes a large portion of total revenue.

---

## 📁 Repository Structure


---

## ▶️ How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/Faizan9-ai/food-delivery-data-analysis.git



