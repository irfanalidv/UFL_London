
# UFL_London
Customer Purchase Classification from scratch

- **Predictive model for purchase classification based on this calculation at what point in time should a user be pushed a Diamond Club offer?**

# Let us understand 

**This is Dataset for First Transaction done [  iap | diamond club ]**

![fist_trans](https://user-images.githubusercontent.com/5808185/36059889-c48418fc-0e63-11e8-92e6-c459eaf5d851.PNG)

**Now we Train the Machine to understand the User transaction behavior**

![confusion matrix](https://user-images.githubusercontent.com/5808185/36060093-0e427d40-0e68-11e8-9092-73e97e917a04.PNG)

**we than find the list of predicted value in which purchase purchase type is Diamond Club **

![predicted_value](https://user-images.githubusercontent.com/5808185/36060292-a460b9be-0e6c-11e8-9ec9-2ade4beef57c.PNG)

**From the above data, we find the driven factor for the transaction with repect to the games_before_purchase | balance_before_purchase**

![centre](https://user-images.githubusercontent.com/5808185/36060306-e048601c-0e6c-11e8-95f8-48b6ceeedc5b.PNG)

 **Then we check for which cluster the purchase type is diamond | **
**we see that Cluster 6 has the Prediction of Diamond Club purchase**

![cluster6](https://user-images.githubusercontent.com/5808185/36060318-32c67496-0e6d-11e8-96b7-1ce006c20a36.PNG)

**We extract all the values combination of games_before_purchase | balance_before_purchase in cluster 6**

![cluster6_value](https://user-images.githubusercontent.com/5808185/36060328-7dc93974-0e6d-11e8-9eed-2fbe64c3c611.PNG)

**Now we check for our prediction and feed this combination in machine to check how true the different combination is performing**

![desire_value_diamong](https://user-images.githubusercontent.com/5808185/36060340-ac02c6e8-0e6d-11e8-8a57-0b5315974d24.PNG)

#Hence this is the desire value for Diamon purchase
