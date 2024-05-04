
<h1>Financial News and Stock Price Integration</h1>

<h2>Description</h2>
<p>This repository contains code and analysis for integrating financial news data with stock price data.</p>

<h2>Author</h2>
<p>Author: Mihret Agegnehu</p>

<h2>Folder Structure</h2>
<pre>
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
</pre>

<h2>Tasks and Deliverables</h2>

<h3>Task 1: Git and GitHub</h3>
<h4>Tasks</h4>
<ul>
    <li>Setting up Python environment</li>
    <li>Git version control</li>
    <li>CI/CD</li>
</ul>
<h4>Key Performance Indicators (KPIs)</h4>
<ul>
    <li>Dev Environment Setup</li>
    <li>Relevant skill in the area demonstrated</li>
</ul>
<h4>Minimum Essential To Do</h4>
<ul>
    <li>Create a GitHub repository that you will be using to host all the code for this week.</li>
    <li>Create at least one new branch called "task-1" for your analysis of day 1.</li>
    <li>Commit your work at least three times a day with a descriptive commit message.</li>
    <li>Perform Exploratory Data Analysis (EDA) analysis on the following:</li>
    <ul>
        <li><strong>Descriptive Statistics:</strong>
            <ul>
                <li>Obtain basic statistics for textual lengths (like headline length).</li>
                <li>Count the number of articles per publisher to identify which publishers are most active.</li>
                <li>Analyze the publication dates to see trends over time, such as increased news frequency on particular days or during specific events.</li>
            </ul>
        </li>
        <li><strong>Text Analysis (Sentiment analysis & Topic Modeling):</strong>
            <ul>
                <li>Perform sentiment analysis on headlines to gauge the sentiment (positive, negative, neutral) associated with the news.</li>
                <li>Use natural language processing to identify common keywords or phrases, potentially extracting topics or significant events (like "FDA approval", "price target", etc.).</li>
            </ul>
        </li>
        <li><strong>Time Series Analysis:</strong>
            <ul>
                <li>How does the publication frequency vary over time? Are there spikes in article publications related to specific market events?</li>
                <li>Analysis of publishing times might reveal if there’s a specific time when most news is released, which could be crucial for traders and automated trading systems.</li>
            </ul>
        </li>
        <li><strong>Publisher Analysis:</strong>
            <ul>
                <li>Which publishers contribute most to the news feed? Is there a difference in the type of news they report?</li>
                <li>If email addresses are used as publisher names, identify unique domains to see if certain organizations contribute more frequently.</li>
            </ul>
        </li>
    </ul>
</ul>


<h3>Task 2: Stock Price Fetching using yfinance</h3>
<h4>Tasks</h4>
<ul>
    <li>Load and prepare the data.</li>
    <li>Load your dataset containing stock symbols and dates from a CSV file into a pandas DataFrame.</li>
    <li>Convert the 'date' column to datetime objects to facilitate date manipulation.</li>
    <li>Determine date ranges and fetch stock data.</li>
    <li>Calculate the earliest and latest date for each stock to define the period for which to fetch stock prices.</li>
    <li>Use yfinance to download stock data for each stock based on the calculated date ranges.</li>
</ul>
<h4>Key Performance Indicators (KPIs)</h4>
<ul>
    <li>Proactivity to self-learn - sharing references.</li>
    <li>Completeness of Data.</li>
    <li>Data Coverage.</li>
</ul>
<h4>Minimum Essential To Do</h4>
<ul>
    <li>Merge the necessary branches from task-1 into the main branch using a Pull Request (PR).</li>
    <li>Create at least one new branch called "task-2" for the ongoing development of the dashboard.</li>
    <li>Commit your work with a descriptive commit message.</li>
</ul>
<h4>Prepare Your Data</h4>
<ul>
    <li>Identify Stock Symbols and Date Ranges.</li>
    <li>Fetch Stock Prices.</li>
</ul>

<h3>Task 3: Quantitative Analysis using quantstat and TaLib</h3>
<h4>Tasks</h4>
<ul>
    <li>Load and prepare the data.</li>
    <li>Load your stock price data into a pandas DataFrame. Ensure your data includes columns like Open, High, Low, Close, and Volume.</li>
    <li>Apply Analysis Indicators with TA-Lib:
        <ul>
            <li>Calculate various technical indicators such as moving averages, RSI (Relative Strength Index), and MACD (Moving Average Convergence Divergence) using TA-Lib.</li>
        </ul>
    </li>
    <li>Use Quantstat for Financial Metrics.</li>
    <li>Visualize the Data: Create visualizations to better understand the data and the impact of different indicators on the stock price.</li>
</ul>
<h4>Key Performance Indicators (KPIs)</h4>
<ul>
    <li>Proactivity to self-learn - sharing references.</li>
    <li>Accuracy of indicators.</li>
    <li>Completeness of Data Analysis.</li>
</ul>
<h4>Minimum Essential To Do</h4>
<ul>
    <li>Merge the necessary branches from task-2 into the main branch using a Pull Request (PR).</li>
    <li>Create at least one new branch called "task-3" for the ongoing development of the dashboard.</li>
    <li>Commit your work with a descriptive commit message.</li>
</ul>
<h4>Prepare Your Data</h4>
<ul>
    <li>Calculate Basic Technical Indicators.</li>
    <li>Visualize Data.</li>
</ul>


<h3>Task 4: Correlation between News and Stock Movement</h3>
<h4>Tasks</h4>
<ul>
    <li>Date Alignment: Ensure that both datasets (news and stock prices) are aligned by dates. This might involve normalizing timestamps.</li>
    <li>Sentiment Analysis: Conduct sentiment analysis on news headlines to quantify the tone of each article (positive, negative, neutral). Tools: Use Python libraries like nltk, TextBlob for sentiment analysis.</li>
    <li>Analysis:
        <ul>
            <li>Calculate Daily Stock Returns: Compute the percentage change in daily closing prices to represent stock movements.</li>
            <li>Correlation Analysis: Use statistical methods to test the correlation between daily news sentiment scores and stock returns.</li>
        </ul>
    </li>
</ul>
<h4>Key Performance Indicators (KPIs)</h4>
<ul>
    <li>Proactivity to self-learn - sharing references.</li>
    <li>Sentiment Analysis.</li>
    <li>Correlation Strength.</li>
</ul>
<h4>Minimum Essential To Do</h4>
<ul>
    <li>Merge the necessary branches from task-3 into the main branch using a Pull Request (PR).</li>
    <li>Create at least one new branch called "task-4" for the ongoing development of the dashboard.</li>
    <li>Commit your work with a descriptive commit message.</li>
</ul>
<h4>Data Preparation</h4>
<ul>
    <li>Normalize Dates: Align dates in both news and stock datasets to ensure each news item matches the corresponding stock trading day.</li>
    <li>Perform Sentiment Analysis: Use a simple and effective sentiment analysis tool to assign sentiment scores to headlines.</li>
</ul>
<h4>Calculate Stock Movements</h4>
<ul>
    <li>Compute Daily Returns: Calculate daily percentage changes in stock prices to represent movements.</li>
    <li>Correlation Analysis</li>
</ul>



