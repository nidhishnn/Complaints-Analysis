# Complaints-Analysis

For this project, I am analyzing a publicly available consumer complaint dataset from the Consumer Financial Protection Bureau. The dataset included the following features:

1. Date received: The date the CFPB received the complaint
2. Product: The type of product the consumer identified in the complaint
3. Sub-product: The type of sub-product the consumer identified in the complaint
4. Issue: The issue the company identified in the complaint
5. Sub-issue: The sub-issue the consumer identified in the complaint
6. Consumer complaint narrative: Consumer-submitted description of "what happened" from the complaint
7. Company public response: The company's optional, public-facing response to consumer complaint
8. Company: The complaint is about this company
9. State: The state of the mailing address provided by the consumer
10. ZIP code: The mailing ZIP code provided by the consumer
11. Tags: Data that supports easier searching and sorting of complaints
12. Consumer consent provided?: Identifies whether consumer opted in to publish complaint narrative
13. Submitted via: How complaint was submitted to CFPB
14. Date sent to company: Date CFPB sent complaint to company
15. Company response to consumer: This is how the company responded
16. Timely response?: Whether the company gave a timely response
17. Consumer disputed?: Whether the consumer disputed the company's response
18. Complaint ID: Unique identification number for complaint

I formulated the research question: How can the CFPB develop a targeted approach to addressing 800,000+ annual consumer complaints?
I investigated 5000 rows of 2022 consumer complaint data to address the research question. In the exploratory analysis section, I created plots and pivot tables to understand trends in the dataset using the _pandas_ package. Then, I wanted to parse the Consumer complaint narrative feature using _spaCy_. I lemmatized nouns, verbs, and adjectives found in each consumer complaint and leveraged topic modeling techniques to identify significant patterns and consumer's primary complaint concerns. 
