# TripleTen Sprint X Project – EDA & Forecasting

This project was part of the TripleTen Data Science program. It combined exploratory data analysis with forecasting and business recommendations — one of the most comprehensive analytical projects I’ve completed so far.

---

## Video Game Sales Forecasting

The goal of the project was to analyze historical global video game sales, identify platform, genre, and regional trends, and use those insights to forecast potential sales for 2017. The project concludes with data‑driven marketing recommendations for the fictional game publisher *Ice*.

---

## The Data

The dataset was adapted by TripleTen from a Kaggle source and includes video game sales across multiple regions. It contains the following fields:

### vgsales.csv  
Each row represents a single video game title.

- **Name**: Title of the game  
- **Platform**: Console or system the game was released on  
- **Year_of_Release**: Release year  
- **Genre**: Game genre (Action, Sports, RPG, etc.)  
- **Publisher**: Publishing company  
- **NA_Sales**: Sales in North America (millions)  
- **EU_Sales**: Sales in Europe (millions)  
- **JP_Sales**: Sales in Japan (millions)  
- **Other_Sales**: Sales in other regions (millions)  
- **Global_Sales**: Total worldwide sales (millions)  
- **Critic_Score**: Average critic rating  
- **User_Score**: Average user rating  
- **Rating**: ESRB rating (E, T, M, etc.)

The dataset spans multiple console generations and includes both commercial performance and user/critic sentiment.

---

## The Process

I began by exploring the dataset to understand its structure, identify missing values, and check for duplicates or inconsistencies. After cleaning and preparing the data, I performed a full exploratory analysis to uncover:

- Platform performance over time  
- Genre popularity across regions  
- Regional differences in player preferences  
- Relationships between critic/user scores and sales  
- Trends that could inform 2017 forecasting  

I then built a forecasting approach using historical patterns to estimate which platforms and genres were most likely to succeed in 2017.

---

## Results

This project helped me practice not only technical analysis but also communicating insights clearly. I wrote an introduction and conclusion summarizing the findings and provided recommendations for Ice’s 2017 marketing strategy, including:

- Prioritizing platforms with strong historical performance  
- Focusing on genres with consistent global demand  
- Leveraging user and critic ratings to guide product positioning  
- Tailoring marketing strategies to regional preferences  

Please have a look at the Jupyter Notebook included for a full description of results.
