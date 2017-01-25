#Data Overview 
To determine the sentiment towards iPhone products and Samsung Galaxy devices I turned to the worldwide web to build a data set. Common Crawl is an open repository of web crawl data that is stored in Amazon’s Public Data Sets. Using this pubic data set I was able to scrape hundreds of thousands of web pages in order to find those with possible reviews for our targeted smartphone products. A web page was only kept in the new large data matrix if it mentioned the smartphone device name and a review term such as “review, critique, looks at, in depth, analysis, evaluate, evaluation, and assess”. 

Positive, negative, or uncertain reviews were then determined by such words as “awesome, excellent, outstanding, pleased, awful, bad, cumbersome, error, terrible, sometimes, tentative, uncertain, undecided” and many others. Through trial and error, I determined that review terms must be within 5 words of the feature or device name in order to get valid review data, but also not limit the data set too severely. 

Using all of this gathered data, a team of individuals manually labeled a small set of data (compiled using the above criteria) with a sentiment rating from a scale of 1-5 with 5 being excellent, 3 being mediocre, and 1 being bad.  This team manually read through each page in order to assign a sentiment score. With these two small labeled data sets being correctly labeled, I am now able to use classification to train a model to predict a sentiment score for the each row of large data matrix, which has over 150,000 rows of data. 

Continue to [Classification] (https://github.com/chelswhite84/Sentiment-Analysis/blob/master/Steps/Classification.md) 

Return to [Background] (https://github.com/chelswhite84/Sentiment-Analysis/blob/master/Steps/Background.md) 
