#  Sales Prediction Using Python

---

## The Story Behind This Project

Imagine a small startup. They have a dream, a product, and a limited budget. They decide to advertise  on TV, on Radio, and in Newspapers. Months pass. Sales come in. But they have no idea **which advertisement actually worked.**

They spent money everywhere, hoping something would stick. Some channels worked. Some didn't. But without data, they'll never know  and next month, they'll make the same mistake again.

This is the problem I wanted to solve.

---

##  What is This Project?

This is a **Sales Prediction Machine Learning project** built in Python. It takes a company's advertising spend across three channels  **TV, Radio, and Newspaper**  and predicts how much **Sales** that spending will generate.

It also tells you **which channel is giving the best return on investment**  so you know exactly where your money is working hardest.

---

##  Why Did I Build This?

Every business big or small spends money on advertising. But most early-stage startups and small businesses do this blindly. They don't have a data team. They don't have insights. They just spend and hope.

The reality is harsh **wrong advertising decisions can drain a startup's entire budget** before they even find their first 100 customers.

I built this project to answer one simple but powerful question:

> *"If I spend X amount on TV, Y on Radio, and Z on Newspaper how much sales can I expect?"*

---

##  The Problem I Am Solving

A startup is about to launch. They have ₹50,000 set aside for advertising. They have three options — TV, Radio, and Newspaper. They don't know:

- Which channel will give them the most sales?
- Is Newspaper advertising even worth it?
- Should they put everything into TV or split it?

Without answers, they gamble. With this project, they **don't have to.**

This model analyzes historical advertising data and learns the relationship between **ad spend and sales** so any business can make smarter, data-backed decisions before spending a single rupee.

---

##  How I Solved It

### Step 1 — Understanding the Data
I used the **Advertising dataset** which contains real records of how much a company spent on TV, Radio, and Newspaper ads and what sales they generated each time.

### Step 2 — Exploring the Data
I analyzed patterns, distributions, and relationships between each advertising channel and sales. Key finding: **TV has the strongest impact on sales. Newspaper has the weakest.**

### Step 3 — Cleaning the Data
I handled outliers in the Newspaper column using a capping technique so they don't mislead the model.

### Step 4 — Building Prediction Models
I trained three machine learning models:
- **Linear Regression** — simple and interpretable baseline
- **Random Forest Regressor** — handles complex patterns
- **Gradient Boosting Regressor** — best performing model

### Step 5 — Finding the Best Channel (ROI Analysis)
I calculated the **Return on Investment (ROI)** for each advertising channel showing exactly how much sales each unit of spend generates.

---

## 🛠️ Tools & Technologies Used

- **Python**
- **Pandas & NumPy** — data handling
- **Matplotlib & Seaborn** — visualizations
- **Scikit-learn** — machine learning models
- **Jupyter Notebook** — development environment

---

##  Dataset

- **Name:** Advertising.csv
- **Rows:** 200
- **Features:** TV, Radio, Newspaper (ad spend in $thousands)
- **Target:** Sales (units sold in thousands)

---

##  Key Insights

- TV advertising has the **highest impact** on sales
- Radio is the **most cost-efficient** channel (best ROI)
- Newspaper advertising shows **very weak correlation** with sales — not worth heavy investment for a new business
- A startup should prioritize **TV + Radio** and keep Newspaper spending minimal

---

##  Who Is This For?

- Startups trying to allocate their first advertising budget wisely
- Small business owners who want data-backed marketing decisions
- Marketing teams who want to forecast sales before a campaign launches
