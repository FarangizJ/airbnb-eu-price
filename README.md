# Airbnb Prices in European Cities

This project analyzes Airbnb listings across various European cities to identify price trends, understand factors influencing pricing, and determine the most and least expensive destinations.

## Dataset
- **Name:** Airbnb Prices in European Cities  
- **Source:** [Airbnb Europe Datadet](https://www.kaggle.com/datasets/dipeshkhemani/airbnb-cleaned-europe-dataset) 

## Objectives
- Compare average prices across cities
- Identify key factors influencing price
- Visualize price distribution and patterns

## Methodology
- Data cleaning and preprocessing (`pandas`, `numpy`)
- Exploratory data analysis (`matplotlib`, `seaborn`)

## Repository Structure
```
airbnb-eu-price/
│
├── data/
│ ├── raw/ <- abnb_eu.csv <-  untouched data
│ └──- abnb_ue1.csv       <-  data for editing
 
├── notebooks/
│ └── analysis.ipynb      <- Main analysis notebook
│
├── outputs/
│ ├── avg_price_by_city.csv   <- output from notebook
│ └── avg_price_by_city.png   <- output from notebook
│
├── requirements.txt 
├── LICENSE
└── README.md

```

## License

This project is licensed under the MIT License.

## Requirements.txt
pandas
numpy
matplotlib
seaborn
notebook

## analysis.ipynb
