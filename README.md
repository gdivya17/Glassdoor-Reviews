# Glassdoor-Reviews

Glassdoor allows employees to rate and describe their experiences and across several dimensions, but ultimately employees are free to write what they want. These reviews are unstructured and cover various aspects as a whole. The aim is to get phrases out of sentences, classify them according to what aspect it is about, and finally perform sentiment analysis on them to get the opinion about different dimensions from the review. 
1. Built database of Glassdoor reviews by scraping the content using Selenium Webdriver. 
2. The phrases were extracted by POS-tagging and chunking using NLTK. 
3. The phrases were vectorized using Word2Vec embeddings.
4. The reviews were then scored for each class on the basis of similarity of constituent phrases with the defined class phrases.

Working on VADER for sentiment analysis and trying Doc2Vec and Sent2Vec embeddings in place of Word2Vec for better results.
