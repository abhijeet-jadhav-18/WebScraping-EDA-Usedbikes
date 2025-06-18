# WebScraping-EDA-Usedbikes_Credr_Bikes

# 🏍️ Used Bike Price Analysis (Web Scraping + EDA)

This project focuses on web scraping used bike listings and performing exploratory data analysis (EDA) to understand price trends, brand popularity, and other key insights.

## 📄 Dataset
- Collected from CredR using BeautifulSoup.
- Contains data like brand, model, year, kilometers driven, fuel type, price, and location.

## 📊 What This Project Includes
- Data cleaning and preprocessing
- Brand-wise and location-wise price analysis
- Distribution of bike prices and usage
- Trend analysis over bike manufacturing years

## 🧪 Sample Data
| Brand | Model          | Year | KMs Driven | Fuel Type | Price | Location   |
|-------|----------------|------|------------|-----------|-------|------------|
| Honda | CB Shine       | 2018 | 12000      | Petrol    | 55000 | Pune       |
| Bajaj | Pulsar 150     | 2017 | 24000      | Petrol    | 50000 | Mumbai     |
| TVS   | Apache RTR 160 | 2019 | 18000      | Petrol    | 65000 | Bangalore  |

## 🛠️ Tools Used
- Python
- BeautifulSoup
- pandas
- matplotlib & seaborn (for visualization)
- Jupyter Notebook

## 📈 Key Insights
- Bajaj and Hero bikes are among the most listed.
- Prices are strongly influenced by kilometers driven and year of manufacture.
- Pune and Bangalore had the highest number of listings.

## 🚀 How to Run
```bash
link: https://www.credr.com/all-used-bikes-in-Bangalore
cd WebScraping-EDA-BikePrices
pip install -r requirements.txt
jupyter notebook Project_EDA.ipynb
