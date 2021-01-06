# Text Analytics

Tableau Dashboard [Link](https://public.tableau.com/views/RelationshipTextsProject/Dashboard1?:language=en&:display_count=y&publish=yes&:origin=viz_share_link)

## Project Overview
This text mining project to analyzes messages sent from the couple's chatting app called [Between](https://between.us/?lang=en).

| Totals |
|--------|
| 1113 Days |
| 144,011 Messages |
| 694,967 Words |

|          Sender        |    BF   |    GF    |
| --------------------- | ------------- | --------- |
|  Number of Messages  |     80,007    |   64,004  |
|      Word Count    |     384,341    |   310,626  |
|        Avg Message Length        |     24.3    |   24.6  |
|        Avg Messages Per Day        |     89    |   72  |


### Part 1: Data Cleaning and Preprocessing 
* Export data from the app as a text file and then convert to an .xlsx
* Import .xslx file as csv and wrangle into a pandas df
* Extracted following features: date message sent, time message sent, sender name, message body

### Part 2: Basic EDA
* Frequency of total messages sent
* Frequency of messages sent throughout days of the week
* Compared frequency between BF and GF

### Part 3: WordClouds
* Overall WordCloud from all message history
* WordCloud from BF messages vs. WordCloud from GF messages
* Look for common words, themes, patterns

### Part 4: Sentiment Analysis
* Evaluate sentiment scores from Vader
* Evaluate polarity score from TextBlob
* Vader vs. TextBlob comparison
* See changes in sentiment over time

### Part 5: Text Classification
* Find words that best define the overall message history using spaCy
* KMeans clustering to look for common themes/patterns

### Data Visualizations
<img src="images/tableau_dashboard_final.PNG" width=1000>

<img align="center" img src="images/hubby_wc.png" width=400> <img align="center" img src="images/wifey_wc.png" width=400>
