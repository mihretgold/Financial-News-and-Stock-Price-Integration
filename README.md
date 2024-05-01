# Financial-News-and-Stock-Price-Integration

Deliverables and Tasks to be done
Task 1:
Git and GitHub
Tasks: 
Setting up Python environment
Git version control 
CI/CD 
Key Performance Indicators (KPIs):
Dev Environment Setup.
Relevant skill in the area demonstrated.
Suggested folder structure:
├── .vscode/
│   └── settings.json
├── .github/
│   └── workflows
│       ├── unittests.yml
├── .gitignore
├── requirements.txt
├── README.md
├── src/
│   ├── __init__.py
├── notebooks/
│   ├── __init__.py
│   └── README.md
├── tests/
│   ├── __init__.py
└── scripts/
    ├── __init__.py
    └── README.md
Project Planning - EDA & Stats
Tasks: 
Data Understanding
Exploratory Data Analysis (EDA)
Statistical thinking
KPIs:
Proactivity to self-learn - sharing references.
EDA techniques to understand data and discover insights,
Demonstrating Stats understanding by using suitable statistical distributions and plots to provide evidence for actionable insights gained from EDA.

Minimum Essential To Do
Create a github repository that you will be using to host all the code for this week.
Create at least one new branch called ”task-1” for your analysis of day 1
Commit your work at least three times a day with a descriptive commit message
Perform Exploratory Data Analysis (EDA) analysis on the following:
Descriptive Statistics:
Obtain basic statistics for textual lengths (like headline length).
Count the number of articles per publisher to identify which publishers are most active.
Analyze the publication dates to see trends over time, such as increased news frequency on particular days or during specific events.
Text Analysis(Sentiment analysis & Topic Modeling):
Perform sentiment analysis on headlines to gauge the sentiment (positive, negative, neutral) associated with the news.
Use natural language processing to identify common keywords or phrases, potentially extracting topics or significant events (like "FDA approval", "price target", etc.).
Time Series Analysis:
How does the publication frequency vary over time? Are there spikes in article publications related to specific market events?
Analysis of publishing times might reveal if there’s a specific time when most news is released, which could be crucial for traders and automated trading systems.
Publisher Analysis:
Which publishers contribute most to the news feed? Is there a difference in the type of news they report?
If email addresses are used as publisher names, identify unique domains to see if certain organizations contribute more frequently.

Task 2:
Stock price fetching using yfinance
Tasks:
Load and prepare the data.
Load your dataset containing stock symbols and dates from a CSV file into a pandas DataFrame.
Convert the 'date' column to datetime objects to facilitate date manipulation.
Determine date ranges and fetch stock data.
Calculate the earliest and latest date for each stock to define the period for which to fetch stock prices.
Use yfinance to download stock data for each stock based on the calculated date ranges.

KPIs
Proactivity to self-learn - sharing references.
Completeness of Data.
Data Coverage

Minimum Essential To Do:
Merge the necessary branches from task-1 into the main branch using a Pull Request (PR)
Create at least one new branch called "task-2" for the ongoing development of the dashboard.
Commit your work with a descriptive commit message.
Prepare Your Data
Identify Stock Symbols and Date Ranges
Fetch Stock Prices


Task 3:
Quantitative analysis using pynance and TaLib

Tasks:
Load and prepare the data.
Load your stock price data into a pandas DataFrame. Ensure your data includes columns like Open, High, Low, Close, and Volume.	
Apply Analysis Indicators with TA-Lib
You can use TA-Lib to calculate various technical indicators such as moving averages, RSI (Relative Strength Index), and MACD (Moving Average Convergence Divergence)
Use PyNance for Financial Metrics
Visualize the Data
Create visualizations to better understand the data and the impact of different indicators on the stock price.
KPIs
Proactivity to self-learn - sharing references.
Accuracy of indicators
Completeness of Data Analysis

Minimum Essential To Do:
Merge the necessary branches from task-2 into the main branch using a Pull Request (PR)
Create at least one new branch called "task-3" for the ongoing development of the dashboard.
Commit your work with a descriptive commit message.
Prepare Your Data
Calculate Basic Technical Indicators
Visualize Data


Task 4:
Correlation between news and stock movement

Tasks:
Date Alignment: Ensure that both datasets (news and stock prices) are aligned by dates. This might involve normalizing timestamps.
Sentiment Analysis: Conduct sentiment analysis on news headlines to quantify the tone of each article (positive, negative, neutral).Tools: Use Python libraries like nltk, TextBlob for sentiment analysis.
Analysis:
Calculate Daily Stock Returns: Compute the percentage change in daily closing prices to represent stock movements.
Correlation Analysis: Use statistical methods to test the correlation between daily news sentiment scores and stock returns.
KPIs
Proactivity to self-learn - sharing references.
Sentiment Analysis
Correlation Strength



Minimum Essential To Do:
Merge the necessary branches from task-3 into the main branch using a Pull Request (PR)
Create at least one new branch called "task-4" for the ongoing development of the dashboard.
Commit your work with a descriptive commit message.
Data preparation
Normalize Dates: Align dates in both news and stock datasets to ensure each news item matches the corresponding stock trading day.
Perform Sentiment Analysis: Use a simple and effective sentiment analysis tool to assign sentiment scores to headlines.


Calculate Stock Movements
Compute Daily Returns: Calculate daily percentage changes in stock prices to represent movements.
Correlation Analysis


Aggregate Sentiments: Compute average daily sentiment scores if multiple articles appear on the same day.
Calculate Correlation: Determine the Pearson correlation coefficient between average daily sentiment scores and stock daily returns.
