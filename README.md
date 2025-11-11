# 🇨🇦 Canada Immigration Word Cloud Analysis (1980–2013)

This project visualizes immigration trends to **Canada** using a *Word Cloud*, 
where the size of each country's name represents the total number of immigrants 
from that country between **1980 and 2013**.

The notebook demonstrates data analysis, transformation, and visualization skills 
that are essential for any aspiring **Data Analyst**.

---

## 📊 Project Overview

Using the official Canada Immigration dataset provided by IBM Skills Network, 
this project reads, cleans, and analyzes the data to identify immigration trends.  
It then converts the data into a text-based format and visualizes it using a Word Cloud.

---

## 🧠 Objectives

- Load the dataset using **pandas**
- Set "Country" as the index for easy lookup
- Calculate total immigration using **pandas aggregation**
- Generate a **weighted text string** of country names based on immigration counts
- Create and display a **Word Cloud visualization**

---

## ⚙️ Technologies Used

| Library | Purpose |
|----------|----------|
| **Python** | Core language |
| **Pandas** | Data handling and analysis |
| **Matplotlib** | Plotting and displaying the word cloud |
| **WordCloud** | Generating the word cloud image |

---

## 🧱 Steps in the Notebook

1. **Import Libraries** – pandas, matplotlib, wordcloud  
2. **Load Data** – Canadian Immigration dataset from IBM Cloud  
3. **Set Index** – Use `Country` as index  
4. **Aggregate Data** – Compute total immigration (1980–2013)  
5. **Generate Text Data** – Repeat country names proportional to immigration  
6. **Create Word Cloud** – Visualize data using the `WordCloud` library  
7. **Display Result** – Render colorful word cloud using Matplotlib  

---

## 🖼️ Example Output

A colorful word cloud showing each country’s contribution to immigration in Canada.  
Countries with higher immigration numbers (like **India**, **China**, and **Philippines**) 
appear larger in the visualization.

---

## 💼 Why This Project Matters

This project demonstrates:

- Working with **real-world datasets**
- Data cleaning, transformation, and summarization using **pandas**
- Applying **visual storytelling** to make data insights easier to understand
- Confidence in using **Matplotlib** and **WordCloud** for visualization tasks

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/Canada-Immigration-WordCloud-Analysis.git
   
2.Open the Jupyter notebook:
jupyter notebook Word_Cloud_Imigration.ipynb

3.Run all cells.

👤 Author

Vidya Vishnuvihar
Aspiring Data Analyst | IBM Data Analysis Professional Certificate Graduate
📍 Based in Scotland, UK
