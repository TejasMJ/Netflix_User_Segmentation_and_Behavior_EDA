# 📊 Netflix User Behavior & Engagement EDA

A comprehensive **Exploratory Data Analysis (EDA)** of a Netflix user-level dataset using Python, Pandas, Plotly, Seaborn, and Matplotlib to uncover insights around user engagement, subscription behavior, and content preferences.

---

## 🌟 Features

### Core Features
- **Data Cleaning & Preprocessing:** Data type standardization and handling minimal missing values.
- **User Demographic Analysis:** Age and country-level user distribution.
- **Subscription Analysis:** Adoption patterns across Basic, Standard, and Premium plans.
- **Engagement Analysis:** Distribution and concentration of watch time across users.
- **Content Preference Analysis:** Genre-level consumption patterns.
- **Temporal Analysis:** Login recency and engagement timing trends.
- **Visualization:** Interactive and static plots using Plotly, Seaborn, and Matplotlib.

---

## 🗂 Project Structure

The project folder is organized as follows:

```text
Netflix_User_EDA/
├── data
|    ├── netflix_users.csv         # Netflix user-level dataset
├── Netflix_User_EDA.ipynb         # Jupyter Notebook with full EDA
├── requirements.txt               # Python dependencies
└── venv/                          # Virtual environment
```

---

## 🏗️ EDA Architecture

```text
+---------------------------+  
|        DATA LAYER         |  
|  Netflix user dataset    |  
|      (CSV format)        |  
+------------+--------------+  
             ↓  
+------------------------------+  
|       ANALYSIS LAYER         |  
|  - Data Cleaning             |  
|  - Demographic Analysis      |  
|  - Subscription Analysis    |  
|  - Engagement Analysis      |  
|  - Genre Preferences        |  
|  - Time-based Patterns      |  
+------------+-----------------+  
             ↓  
+---------------------------------------+  
|      VISUALIZATION LAYER               |  
|  - Interactive Charts (Plotly)         |  
|  - Static Plots (Seaborn & Matplotlib) |  
|  - Bar Charts, Histograms, Boxplots    |  
+---------------------------------------+  

```

---

## 🛠 Tech Stack

- **Language:** Python 3.8+
- **Libraries:**
  - **Data Manipulation:** Pandas, NumPy
  - **Visualization:** Matplotlib, Seaborn, Plotly
- **Environment:** Jupyter Notebook
- **Data Source:** [Kaggle – Netflix Dataset](https://www.kaggle.com/datasets/ariyoomotade/netflix-data-cleaning-analysis-and-visualization)

---

## 📊 Dataset Overview

## 📊 Dataset Overview

- **Level:** User-level dataset  
- **Columns include:** User_ID, Name, Age, Country, Subscription_Type, Watch_Time_Hours, Favorite_Genre, Last_Login  

**Context:**  
The dataset captures anonymized user demographics, subscription characteristics and viewing behavior enabling analysis of engagement intensity, content preferences, and subscription value across users.

**Acknowledgements:**  
- Dataset from [Kaggle – Netflix Dataset](https://www.kaggle.com/datasets/ariyoomotade/netflix-data-cleaning-analysis-and-visualization)
- User data is anonymized and does not represent real individual accounts.

**Inspiration:**  
Understanding how users engage with content, choose subscription tiers, and consume different genres can help streaming platforms optimize personalization, content strategy, and monetization decisions.

---

## 🚀 Quick Start

### 1. Clone Repository
```bash
git clone https://github.com/TejasMJ/Netflix_User_Segmentation_and_Behavior_EDA.git
```

### 2. Create Virtual Environment

```bash
python -m venv venv
```
### 3. Activate Virtual Environment
#### Windows:
```bash
.\venv\Scripts\activate
```
#### Mac/Linux:
```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```
### 5. Run Notebook

```bash
jupyter notebook
```

# 📊 App Analysis Project

## Key Analyses Performed

### User Distribution Analysis
- Country-wise user distribution
- Age group composition of users

### Subscription Analysis
- Adoption comparison across subscription tiers
- Relationship between subscription type and engagement

### Engagement Analysis
- Watch time distribution and concentration
- Identification of light vs heavy viewers

### Content Preference Analysis
- Genre popularity across users
- Age and subscription-based genre trends

### Temporal Analysis
- Login recency patterns
- Engagement stability and seasonality signals

### Visualization
- Interactive dashboards using **Plotly**
- Static plots using **Seaborn** & **Matplotlib**

## 👨‍💻 Author
**Tejas Jadhav**  

- GitHub: [@tejas-jadhav](https://github.com/TejasMJ)  
- LinkedIn: [Tejas Jadhav](https://www.linkedin.com/in/tejas-m-jadhav/)
