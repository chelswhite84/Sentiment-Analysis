# Classification
To determine which method could best predict sentiment I used 4 different classification models: decision tree, random forest, k nearest neighbor and support vector machines. Their accuracy scores are listed below. These accuracy scores were calculated using the postResample function in R Studio.

![iPhone Results] (https://github.com/chelswhite84/Sentiment-Analysis/blob/master/Images/iPhoneClassificationrRESULTS.png)
![Samsung Results] (https://github.com/chelswhite84/Sentiment-Analysis/blob/master/Images/SamsungGlassificationResults.png)

With the highest accuracy score for both smartphone device, Random Forest was the best model choice to predict sentiment with M5Prime being a very close 2nd. The chosen Random Forest model was then used to predict sentiment values for both iPhone and Samsung Galaxy on the large data matrix build from Common Crawl. Based on these model results, I am 77% confident in the accuracy of the below sentiment predictions. 

The results were somewhat surprising in that sentiment towards the iPhone and Samsung Galaxy are very, very similar. There is only about a 1% difference in sentiment between these two devices as shown in the pie charts below. As you can see, if these charts did not have titles, it would be difficult to tell which was which. 


![iPhone Chart] (https://github.com/chelswhite84/Sentiment-Analysis/blob/master/Images/iPhoneChart.png)
![Samsung Chart] (https://github.com/chelswhite84/Sentiment-Analysis/blob/master/Images/SamsungChart2.png)

