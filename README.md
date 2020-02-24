# [IDMB REVIEWS]()
---
## [ 1. OVERVIEW ]()
[ **1.1 About the data**: ]() 

**- The problem:** IMDB movie review sentiment classification problem.

**- The approach:** I will use RNN and LSTM to solve this.

[ **1.2 About the data**: ]() 

**1. Kaggle datatset:**  IMDB dataset contains 25,000 highly-polar movie reviews (good or bad) for training and the same amount again for testing. The problem is to determine whether a given movie review has a positive or negative sentiment.

---
## [ 2. THE RESULT ](/9lRMLcbMR--joBvR84z5KA)

### *Our model can predict correctly around 90% fruits of three classes. Here was what we learned how to make our model worked.*

[ **2.1 The model**: ]() 
1. Word embedding: this layer is used for map each movie review into a vector domain, and similar meaning word usually has vector close to each others.
2. Padding technique: to control the input length of these vector, we take the max length review and padding the shorter ones with zero.
3. Bidirection layer: instead of using LSTM, I will used Bidirectional so that the model can learn both from the past and the future context.
---



