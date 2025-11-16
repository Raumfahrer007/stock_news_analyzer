# Reddit Sentiment & Stock Returns Analysis

An empirical investigation into the relationship between Reddit sentiment and short-term stock price movements for major technology stocks.

## Project Overview

This project examines whether sentiment from stock-related Reddit posts correlates with weekly stock returns for NVIDIA (NVDA), Tesla (TSLA), and Alphabet (GOOGL). The analysis employs comprehensive statistical testing and visual analysis across multiple sentiment measurement methods.

**Key Question**: Is there a statistically significant correlation between weekly Reddit sentiment scores and weekly stock returns?

## Quick Start

### View Only (No Installation Required)
**All analysis and results can be viewed directly on GitHub:**
- Open `notebooks/stock_news_analyzer_project.ipynb` in this repository
- GitHub will display the complete notebook with code, visualizations, and results
- Perfect for reviewing the methodology and findings without any setup

### Interactive Execution

#### Prerequisites
- Python 3.8+

#### 1. Clone the repository
```bash
git clone https://github.com/Raumfahrer007/stock_news_analyzer.git
cd stock_news_analyzer
```

#### 2. Start Notebook
```bash
jupyter notebook
```

#### 3. Project Structure
- notebooks/stock_news_analyzer_project.ipynb - Complete analysis pipeline from data processing to statistical testing
- notebooks/data/ - Contains processed sentiment and stock return data

#### Key Features
- Multi-method sentiment analysis (VADER, TextBlob, custom dictionaries)
- Weekly aggregation of sentiment and stock returns
- Statistical correlation testing and visualization
- Time-series analysis of sentiment-return relationships

**Requirements**  
Core dependencies include pandas, numpy, matplotlib, seaborn, scikit-learn, nltk, and yfinance. All requirements are listed in the notebook and can be installed as needed.