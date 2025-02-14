# Sentiment Analysis on British Airways Reviews

## Project Overview
This project performs sentiment analysis on customer reviews of British Airways to classify whether the feedback is positive or negative. Understanding customer sentiment is essential for airlines to improve services, address pain points, and enhance customer satisfaction. The project employs text classification models to predict sentiment based on review text, offering insights into the most common issues faced by passengers.

## Technologies Used
- Python: Programming language for text processing and model building
- scikit-learn: For natural language processing (NLP) and machine learning
- NLTK: Natural Language Toolkit for text preprocessing
- TF-IDF Vectorizer: For transforming text into numerical features
- Logistic Regression & Random Forest: For text classification
- Pandas: Data manipulation
- NumPy: Numerical computation
- Matplotlib & Seaborn: For visualizing sentiment distribution and model performance

## How to Run
To replicate this project,
1. Clone the repository to your local machine.
```bash
   git clone https://github.com/B-Taiwo/sentiment-analysis-british-airways.git
```
2. Install the necessary dependencies by running:
```bash
pip install -r requirements.txt
```
3. Open the Jupyter notebook:
```bash
jupyter notebook British_Airways_Reviews.ipynb
```
4. Run the notebook cells sequentially to preprocess the text data, train models, and evaluate performance.

## Project Results
### Key Findings
- The Naive-Bayes classification model achieved a weighted F1-score of 0.71, effectively 
identifying good and bad review ratings. However, it struggled with classifying “Average” 
ratings, likely due to overlap in sentiments.
- Sentiment analysis revealed a polarized distribution of British Airways customer reviews, with 
55% being positive and 45% negative.
- Regional analysis showed that customer dissatisfaction is widespread across the world, 
indicating that challenges such as delays, bad service, and operational inefficiencies are not 
limited to any one region, and should be addressed on a global scale.
- Sentiment trends indicated a noticeable decline after 2019, likely due to the COVID-19 
pandemic and its issues. However, there was a slight improvement in 2024 indicating that 
efforts are being made to improve customer satisfaction.
- The WordClouds and frequency distributions identified “seat”, “service”, and “time” as critical 
aspects, appearing frequently in both positive and negative reviews. These factors directly 
influence customer sentiment.

### Recommendations for British Airways
British Airways can enhance customer satisfaction, improve operational efficiency, and strengthen its 
competitive position in the airline industry by implementing these recommendations:
1. Improve Operational Efficiency: Address complaints about delays and inefficiencies, 
particularly at key places like London.
2. Enhance Customer Comfort: Focus on improving seat comfort, because it appears frequently 
in both positive and negative reviews.
3. Service Training: Invest in staff training to ensure consistent service quality globally.
4. Monitor Sentiment Trends: Continuously analyze sentiment over time to proactively identify 
customer concerns

