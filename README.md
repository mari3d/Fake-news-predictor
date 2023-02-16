# Fake-news-predictor

Group Project

Al Bakaoui Chayma, Amadou Khadidja, Harutyunyan Mariam


## Introduction


Today it is sometimes difficult to know which news, information or journal article says the truth and which ones are fake news. Especially with the apparition of social networks, everyone can write and share whatever he/she wants. 
Our project aims to help to distinguish fake news from real news by using their title and text. 


## Description
To do this, we use 2 differents datasets, one of them contains true news and the other one fake news. 
After, we merge them and make a distribution plot to see how many fake or real articles we have. 
We continue by adding stop words (english stop word using nltk). 
And we finish by making predictions. At first, we only work with titles of our articles, after we work with texts and finally we regroup titles and texts. 


## Conclusion

As conclusion, we can see that we get 3 different prediction depending of the information we use. We remark that the accurcy is weak when we only use titles. We improve it when we use texts but the best accuracy we obtain is when we combine titles to texts. 

