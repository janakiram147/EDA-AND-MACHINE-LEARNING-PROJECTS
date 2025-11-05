# 🏙️ Airbnb Listings EDA Project — New York 2024

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python)
![Pandas](https://img.shields.io/badge/Library-Pandas-yellow?logo=pandas)
![NumPy](https://img.shields.io/badge/Library-NumPy-blue?logo=numpy)
![Matplotlib](https://img.shields.io/badge/Visualization-Matplotlib-orange?logo=plotly)
![Seaborn](https://img.shields.io/badge/Visualization-Seaborn-lightblue?logo=seaborn)
![EDA](https://img.shields.io/badge/Skill-EDA-brightgreen)
![Data Cleaning](https://img.shields.io/badge/Skill-Data-Cleaning-purple)
![Data Visualization](https://img.shields.io/badge/Skill-Data-Visualization-darkgreen)

---

## 📘 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the **New York Airbnb listings (2024)** dataset to uncover pricing patterns, room-type trends, host behavior, and availability insights.  
Using **Pandas**, **NumPy**, **Matplotlib**, and **Seaborn**, the notebook cleans, analyzes, and visualizes large datasets to reveal useful trends for hosts and guests.

![](https://github.com/janakiram147/EDA-AND-MACHINE-LEARNING-PROJECTS/blob/main/Airbnb%20Listings%20EDA%20Project:%20New%20York%202024/New-York-City-Brooklyn-Bridge-Panorama-Juergen-Roth-2.jpg)

---

## 🎯 Objectives
1. Analyze **room types, prices, and availability** across New York’s neighborhoods.  
2. Identify **host behavior** and common listing patterns.  
3. Detect and remove **outliers** in price distribution.  
4. Provide **data-driven recommendations** for guests and hosts.

---

## 📂 Dataset
The dataset contains Airbnb listing information such as:

- **id** – Listing identifier  
- **host_id** – Host unique ID  
- **neighborhood_group** – Borough (e.g., Manhattan, Brooklyn)  
- **latitude / longitude** – Location coordinates  
- **price** – Price per night  
- **room_type** – Room category (Entire home, Private room, etc.)  
- **availability_365** – Days available in a year  
- **reviews_per_month** – Monthly review count  

---

## ⚙️ Steps and Workflow

### 🧹 1. Data Cleaning
- Removed **missing values** and **duplicates**.  
- Fixed incorrect **data types** (`id`, `host_id` as object, `last_review` as datetime).  
- Filtered out **price outliers** above \$1,500 for more accurate visualization.

### 📊 2. EDA and Visualization
1. **Univariate Analysis**  
   - Used `sns.histplot` and `sns.boxplot` for `price`, `availability_365`, and `reviews_per_month`.  
   - Detected skewness and potential outliers.

2. **Bivariate Analysis**  
   - Explored relationships between price, room type, and location using bar plots and scatter plots.  
   - Found Manhattan as the most expensive borough.

3. **Feature Engineering**  
   - Created filtered datasets and summary statistics for clearer analysis.

4. **Visual Insights**  
   - **Heatmaps** for correlation among numeric features.  
   - **Boxplots** and **Histograms** for price distribution.  
   - **Bar charts** showing neighborhood and room type counts.

---

## 📈 Key Insights
1. **Manhattan** has the highest-priced listings, while **Bronx and Queens** are more affordable.  
2. **Entire homes/apartments** dominate the market but are costlier.  
3. **Private rooms** are best for budget travelers.  
4. **High-availability listings** tend to have more reviews and lower prices.  
5. Several **hosts manage multiple listings**, indicating professional operations.

---

## 🧠 Recommendations
### 💼 For Hosts
- Maintain **competitive pricing** and availability to boost bookings.  
- Respond to reviews promptly to improve host ratings.

### 🏡 For Guests
- Prefer **Brooklyn or Queens** for affordable stays.  
- Look for listings with **high review counts** for a better experience.

---

## 🚀 How to Run the Project
```bash
# Clone repository
git clone https://github.com/janakiram147/EDA-AND-MACHINE-LEARNING-PROJECTS.git
cd "Airbnb Listings EDA Project: New York 2024"

# Install dependencies
pip install pandas numpy matplotlib seaborn jupyter

# Run the notebook
jupyter notebook
🔮 Future Enhancements
Build a Machine Learning model to predict prices based on location and features.

Perform Sentiment Analysis on guest reviews.

Develop an interactive dashboard using Plotly or Power BI.

🪪 License
This project is open-source under the MIT License.

📬 Contact
GitHub: janakiram147
Feel free to connect for queries or collaboration.












