# **Strategic Revenue Management** - An Analysis of Hotel Pricing Dynamics in the Online Travel Agent (OTA) Market

## 📑 Table of Contents

- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Installation](#installation)
- [Requirements](#requirements)
- [Usage](#usage)
- [Analysis Components](#analysis-components)
  - [1. Data Preprocessing](#1-data-preprocessing)
  - [2. Price Segmentation](#2-price-segmentation)
  - [3. Exploratory Data Analysis (EDA)](#3-exploratory-data-analysis-eda)
  - [4. Visualizations](#4-visualizations)
- [Key Findings](#key-findings)
- [Business Applications](#business-applications)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Project Overview

This project analyzes hotel pricing data from multiple OTA platforms to uncover crucial relationships between price, ratings, and the competitive landscape. By segmenting the market and comparing platforms, the analysis yields strategic insights that reveal the dominant platforms and cities with the highest price variations, aiming to help OTAs and hotels optimize their pricing strategies.

## Objectives

- Analyze pricing patterns across multiple OTA platforms
- Identify relationships between hotel ratings and pricing
- Segment hotels by price categories (Budget, Mid-Range, Premium, Luxury)
- Discover market leaders and platform dominance
- Identify cities with highest price variations for arbitrage opportunities

## Technologies Used

- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computing
- **Matplotlib & Seaborn** - Static data visualization
- **Plotly** - Interactive visualizations
- **Scikit-learn** - Machine learning and clustering

## Dataset

The analysis uses hotel booking data from multiple OTA platforms:
- Dataset: [`Great deals_Booking Hotels.csv`](https://www.kaggle.com/datasets/reenapinto/great-deals-booking-hotels)
- Encoding: Latin1 (to handle special characters)


### Key Features:
- Hotel/Resort names and types
- Locations (Area and City)
- Ratings and number of reviews
- Prices from 3 different booking websites
- Booking platform information

## Installation

```bash
# Clone the repository
git clone https://github.com/defrijay/Strategic-Revenue-Management.git

# Install required packages
pip install pandas numpy matplotlib seaborn plotly scikit-learn

# Or use requirements.txt
pip install -r requirements.txt
```

## Requirements

Create a `requirements.txt` file with:
```
pandas
numpy
matplotlib
seaborn
plotly
scikit-learn
```

## Usage

1. Place your dataset in the `data/` directory
2. Run the Jupyter notebook or Python script:

```bash
jupyter notebook analysis.ipynb
# or
python analysis.py
```

## Analysis Components

### 1. Data Preprocessing
- Cleaning rating and review data
- Price column standardization
- City extraction from location data
- Creating aggregated metrics (Avg_Price, Min_Price, Max_Price, Price_Range)
- Hotel segmentation by price category

### 2. Price Segmentation
Hotels are categorized into 4 segments:
- **Budget**: < $10,000
- **Mid-Range**: $10,000 - $20,000
- **Premium**: $20,000 - $40,000
- **Luxury**: > $40,000

### 3. Exploratory Data Analysis (EDA)

#### Key Insights Generated:
- **Descriptive Statistics**: Total hotels, cities, average ratings and prices
- **Price Distribution**: Box plots showing price variation by segment
- **Rating vs Price Correlation**: Scatter plot analysis
- **Top Cities**: Bar chart of most expensive cities
- **Platform Market Share**: Pie chart of booking platform dominance
- **Review Distribution**: Customer engagement patterns
- **Platform Price Comparison**: Average prices across different OTAs
- **Price Variation Analysis**: Cities with highest arbitrage opportunities

### 4. Visualizations

The project generates multiple visualization types:
- Box plots for price distribution
- Scatter plots for correlation analysis
- Bar charts for comparative analysis
- Pie charts for market share
- Histograms for distribution analysis
- Log-scale plots for skewed data

## Key Findings

The analysis reveals:
1. **Market Leaders**: Dominant OTA platforms by market share
2. **Premium Markets**: Cities with highest average hotel prices
3. **Price Arbitrage**: Cities with significant price variations across platforms
4. **Rating-Price Relationship**: Correlation between hotel quality and pricing
5. **Customer Engagement**: Distribution patterns of reviews and ratings

## Business Applications

This analysis can help:
- **OTA Platforms**: Optimize competitive pricing strategies
- **Hotels**: Understand market positioning and pricing opportunities
- **Revenue Managers**: Identify high-value markets and segments
- **Investors**: Assess market opportunities in different cities
- **Travelers**: Find the best deals across platforms

## Future Enhancements

- Implement predictive pricing models using machine learning
- Add time-series analysis for seasonal pricing trends
- Integrate sentiment analysis from customer reviews
- Build recommendation systems for optimal platform selection
- Create interactive dashboards using Dash or Streamlit

## Creators

Defrizal Yahdiyan Risyad

## Contact

defrijay@gmail.com

