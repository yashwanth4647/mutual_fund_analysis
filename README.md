# mutual_fund_analysis

**Overview**
Objective - To create a mutual fund investment plan based on high ROI and low risk using Python.
Data Cleaning - Checked for missing values in the dataset.
Data Analysis - Calculated volatility, growth rate, and ROI for each company, then identified companies with high ROI and low risk.
Insights - Companies with high ROI and low volatility are suitable for long-term, stable growth.
Deliverable - A mutual fund plan recommending investment ratios for selected companies and a projection of expected returns over time.

**Summary**
Data Collection & Cleaning - Loaded Nifty 50 closing prices from a CSV file and converted the 'Date' column to datetime format. Checked for and confirmed no missing values in the dataset.
Data Analysis - Calculated the standard deviation of closing prices as a measure of volatility, the percentage change as a measure of growth rate, and the overall return on investment (ROI) for each company.
Data Visualization - Visualized stock price trends over time using line plots. Compared the risk and expected ROI of the selected mutual fund companies against high growth rate companies using bar plots.
Trend Analysis - Observed that stock prices fluctuate over time, with some companies showing higher volatility than others. High growth rate companies tend to have higher volatility, while the selected mutual fund companies exhibit lower volatility and moderate returns, suitable for long-term, stable growth.

Summary - Developed a mutual fund plan by selecting companies with ROI above the median and volatility below the median. Calculated investment ratios based on inverse volatility, giving higher weight to less volatile companies. Projected the accumulated value of monthly investments with annual increases over various time periods, demonstrating the power of compounding for long-term investors.
