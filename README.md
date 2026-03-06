# Earnings Call Sentiment Analysis and Stock Market Reaction

This project analyzes the relationship between the sentiment expressed during corporate earnings calls and subsequent stock price movements. The goal is to investigate whether the tone used by company executives during earnings calls can provide signals related to stock market performance.

## Project Overview

1. Collect earnings call transcripts
2. Extract CEO and CFO speeches
3. Perform sentiment analysis using an NLP model
4. Compute quarterly sentiment scores
5. Compare sentiment with stock price performance
6. Perform statistical analysis

## Data Sources

Two main sources were used: 
- Source: *The Motley Fool*.  
Transcripts were manually cleaned to keep only **CEO and CFO speeches**, removing analysts’ questions and other participants.
- Source: *Investing.com*.  
Historical stock price data was collected for the same periods as the earnings calls.

## Companies Analyzed

The analysis focuses on the following companies:

- Microsoft  
- Tesla  
- Apple  

Quarterly earnings calls from **2020 to 2024** were analyzed.
Because earnings calls are long texts, transcripts were divided into smaller chunks before processing. Sentiment scores were then aggregated to obtain a **quarterly sentiment score** for each company.

### Stock Price Analysis, Statistics, Technologies and Libraries
Historical stock prices were aligned with the same quarters as the earnings calls. Using **Pandas, NumPy and SciPy**, we evaluated potential relationships between sentiment scores and stock price movements through statistical correlation analysis.
Results were visualized using **Matplotlib** to show sentiment trends, stock price evolution and potential correlations.

The project was developed in **Python using Google Colab**.
Main libraries used:

- transformers  
- docx2txt  
- pandas  
- numpy  
- matplotlib  
- scipy  
