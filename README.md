# 🚗 eBay Used Car Sales Analysis

![GitHub](https://img.shields.io/badge/Python-3.8%2B-blue)
![GitHub](https://img.shields.io/badge/Libraries-Pandas%20%7C%20Matplotlib%20%7C%20Seaborn-orange)

## 📌 Project Overview
Analysis of 50,000 used car listings from **eBay Kleinanzeigen** (Germany, 2015-2016) to uncover market trends in pricing, brand popularity, and mileage impact.

## 🔍 Key Questions Answered
1. **What are the most popular car brands?**
2. **Which brands command the highest prices?**
3. **How does mileage affect car prices?**

---

## 🛠️ Tools & Libraries
| Category       | Tools                                                                 |
|----------------|-----------------------------------------------------------------------|
| Data Cleaning  | `pandas`, `numpy`                                                    |
| Visualization  | `matplotlib`, `seaborn`                                              |
| Environment    | Jupyter Notebook                                                     |

---

## 📊 Key Findings
### 🏆 Top 3 Popular Brands
1. Volkswagen (9,238 ads)
2. BMW (5,056 ads)
3. Mercedes-Benz (4,361 ads)

### 💰 Most Expensive Brands (Avg. Price)
| Brand       | Average Price |
|-------------|---------------|
| Porsche     | $34,296       |
| Land Rover  | $18,519       |
| Jeep        | $11,621       |

### 📉 Price vs. Mileage
| Mileage Group | Avg. Price |
|---------------|------------|
| 50,000 km     | $14,651    |
| 100,000 km    | $9,634     |
| 150,000 km    | $4,426     |

### 📂Project Structure
```
ebay-cars-analysis/
├── data/
│   ├── raw/autos.csv          # Original dataset
│   └── clean/auto_cars.csv    # Cleaned output
├── E_Bay_Cars_Project.ipynb   # Full analysis
└── README.md                  # This file
```
