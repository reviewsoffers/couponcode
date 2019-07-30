# coupon
This is a project that is still in progress.

# aims
Make a recommendation system for personalized promotional information.

# schedule
#####1.The core of the reptile part. 
#####2.The website homepage and comments are crawled.√  
#####3.Use jdk's httpServer to provide services.√  
#####4.~~Create a web-side project and collect user logs. ~~ (Inconvenient use)
#####5.Use weka for subsequent data processing. √  


# Training set
The finished csv dataset is in the data directory.
#####Classification
According to the view buy normal dislike classification, the data set is not balanced, using the smooth or cost-sensitive method does not feel very good;
Temporarily according to the view buy dislike classification.
#####result
The best result of i148 is based on the decision tree of attribute selection, the correct rate is 82%
The best result of i244 is Naive Bayes, with a correct rate of 77%.

# Other
#####1. Added b-crawl function, including: archive reply user fav
#####2. Provide mxbean calls

For My Latest Project Visit https://www.reviewsoffers.com/
