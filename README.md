# Stock Chart Analysis with ChatGPT

![Image of a robot looking at a stock candlestick chart](robotstockchart.webp)

### about-this-project :information_source:

This is a Python based project that helps get stock market information, plot the data on a chart, and later analyze the graph for position.

### features :hammer_and_wrench:

+ Fetches stock data from Alpha Vantage API
  
+ Plots the data on a candlesticks chart using plotly
  
+ Sends the image of the chart to OpenAI API for analysis
  
+ Returns response from ChatGPT of whether to go long or short on the stock

### installation :arrow_down:

1. Create a new environment and install the necessary libraries from `requirements.txt` file by downloading it to a folder and using the following command on terminal after activating the environment
   
   ```
   pip install -r requirements.txt
   ```
   
2. Get API keys from [Alpha Vantage](https://www.alphavantage.co/) and [OpenAI](https://platform.openai.com/docs/overview). Create `.env` file in the root directory of the project and lines to it. Also, keep the `.env` file somewhere safe or use `.gitignore` for it
   
   ```
   AV_KEY = "Your Alpha Vantage API key goes here"
   OA_KEY = "Your OpenAI API key goes here"
   CHART_PATH = "The path to image of the stock chart goes here"
   ```
   
3. Clone the repository using the following lines of code on your terminal.
   
   ```
   git clone https://github.com/deVishv/stock_chart_analysis_project
   ```

### usage :computer:

1. Input any stock ticker from NYSE or NASDAQ in either lowercase or uppercase
   
2. Save the screenshot of the candlesticks chart and make sure that the `CHART_PATH` variable in `.env` file matches the path of the image
   
3. Run the last chunk and it will give out a response by gpt-4o-mini.

### roadmap :world_map:

- [ ] automate the entire script
      
- [ ] add volume bars
      
- [ ] add technical indicators
      
- [ ] build a stock chart Python app with AI integration

### built by vishv kansagara
