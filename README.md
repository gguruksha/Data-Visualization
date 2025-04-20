# Data-Visualization

# 🏙️ London Airbnb Dashboard — Interactive Data Explorer

This project presents an interactive dashboard built using Dash and Plotly for exploring Airbnb listings across London. The goal is to uncover insights about pricing trends, availability, property types, and neighborhood characteristics.

---

## 📌 Overview

Using real Airbnb listing data, this dashboard enables users to:

- 🔍 Filter listings by neighborhood, property type, and host traits
- 📊 Explore price distribution and availability
- 🗺️ Visualize geospatial patterns on an interactive map
- 📈 Analyze combined patterns with a customizable multi-feature tab

---

## 🧰 Tech Stack

- Python  
- Dash & Plotly for the interactive frontend  
- Pandas for data processing  
- Mapbox & Plotly Express for visualization  

---

## 🧠 Features

### Tab 1: Neighbourhood Map

- Dropdown to select one or multiple London neighborhoods  
- Mapbox scatter plot of listings colored by price  
- Size represents number of reviews

### Tab 2: Price Distribution

- Range slider to filter by price  
- Histogram of listing prices  
- Dynamic update based on selected neighborhoods

### Tab 3: Property Type Overview

- Radio buttons to select property types  
- Bar chart showing listing count by neighborhood for the selected type

### Tab 4: Overall App View

A powerful all-in-one visual exploration tab where users can:

- Select property types (multi-select)
- Choose price range via slider
- Filter by availability window (30, 60, 90, 365 days)
- Toggle host characteristics (superhost, profile pic, identity verified)
- View aggregated stats:
  - 📈 Average availability
  - 💷 Average price
  - 🏠 Number of properties
- Interactive bar chart per neighborhood with hover insights
---

---

## 📈 Dataset

- 📁 Source: Kaggle Airbnb London dataset  
- ~50,000 listings  
- Cleaned and filtered for missing values, data consistency, and type conversion  

---

## 👩‍💻 Author

Built and maintained by **Guruksha Gurnani**  
📍 Master’s in Data Science, George Washington University  
🌐 GitHub: [@gguruksha](https://github.com/guruksha)  
📫 LinkedIn: [linkedin.com/in/gurukshagurnani](https://www.linkedin.com/in/gurukshagurnani/)

---

