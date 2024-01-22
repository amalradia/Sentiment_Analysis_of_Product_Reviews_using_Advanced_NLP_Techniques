Summary
This study explores the application of machine learning and natural language processing (NLP) techniques to perform sentiment analysis on consumer reviews of Amazon products. The focus is on uncovering patterns, emotions, and themes within the textual data of product evaluations. The dataset, sourced from data.world, includes various product-related features.

Dataset
Source: Consumer reviews of Amazon products
Features: Product details, review information, and user-related data.
Target Variable: 'reviews.text' (textual content of reviews)
Exploratory Data Analysis (EDA)
Loaded necessary packages into Jupyter Notebook.
Examined the first 5 rows of the dataset.
Identified missing values using isnull() and .sum() functions.
Focused on 'reviews.text,' which had no missing values, given the study's emphasis on sentiment analysis.
Preprocessed text using techniques like converting to lowercase, removing special characters, tokenizing, removing stop words, and stemming.
Applied the VADER sentiment intensity analyzer to evaluate sentiment scores (Compound, Negative, Positive, Neutral).
Visualized sentiment scores using histplots.
Analyzed sentiment distribution and prevalence for both negative and positive sentiments.
Results
Negative Sentiments:

Mean: 8.68, indicating a skewed distribution with a majority of products having lower counts of negative sentiments.
High standard deviation suggests variability, with some products having significantly higher negative sentiment counts.
Maximum count of 388 implies products with a high number of negative sentiments.
Positive Sentiments:

Mean: 25.76, right-skewed distribution with a concentration of products having lower counts of positive sentiments.
High standard deviation indicates variability, with some products having notably higher positive sentiment counts.
Maximum count of 542 suggests products with exceptionally high positive sentiments.
Conclusion
This study provides insights into consumer sentiments through advanced NLP techniques applied to Amazon product reviews. By navigating data challenges and focusing on relevant columns, we maintained the integrity of sentiment-related data. The results highlight the diversity and complexity of consumer sentiments, emphasizing the significance of methodological choices and data integrity in deriving actionable insights for businesses. The study contributes to understanding patterns in consumer sentiments and offers a framework for businesses to enhance product understanding and meet customer expectations in the digital age.
