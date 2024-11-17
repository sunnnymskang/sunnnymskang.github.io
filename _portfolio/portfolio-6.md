---
title: "ChillPill"
excerpt: "A web app that recommends anti-depressants based on patients’ symptoms and the most common side effects from taking pills: [link to code](https://github.com/sunnnymskang/ChillPillV1)"
collection: portfolio
---
[ChillPill repository on GitHub](https://github.com/sunnnymskang/ChillPillV1)

As an Insight fellow, I built ChillPill, a web app that recommends anti-depressants based on patients’ symptoms and 
the most common side effects from taking pills. Rather than recommending anti-depressants for therapeutic purpose, 
I aimed for this website to be used so that patients can further consult with their doctors. In summary, I 
* Extracted side effects from patient survey data using topic modeling, and infered their prevalence from the corpus of
patient experience
* Engineered features from 17,000 subreddit comments collected through Pushshift Reddit API using NLP methods
including TF-IDF, word2vec and sentiment analysis
* Built a recommendation system that is trained on words associated with positive experiences for a given drug.
Employed Logistic regression and linear SVC for the classification
* Built an inter-active user interface with Flask, Bootstrap and AWS  
The repository for this project is shared 






