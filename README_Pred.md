
# UFL_London
Customer Purchase Classification from scratch

- **Predictive model for purchase classification based on this calculation at what point in time should a user be pushed a Diamond Club offer?**

# Let us understand 

**This is Dataset for First Transaction done [  iap | diamond club ]**

![fist_trans](https://user-images.githubusercontent.com/5808185/36059889-c48418fc-0e63-11e8-92e6-c459eaf5d851.PNG)

**Now we Train the Machine to understand the User transaction behavior**

![confusion matrix](https://user-images.githubusercontent.com/5808185/36060093-0e427d40-0e68-11e8-9092-73e97e917a04.PNG)

**we than find the list of predicted value in which purchase purchase type is Diamond Club**

![predicted_value](https://user-images.githubusercontent.com/5808185/36060292-a460b9be-0e6c-11e8-9ec9-2ade4beef57c.PNG)

**From the above data, we find the driven factor for the transaction with repect to the games_before_purchase | balance_before_purchase**

![new_centre](https://user-images.githubusercontent.com/5808185/36061564-f490bef6-0e81-11e8-869b-9e44f506842d.PNG)

**cluster of combination for Diamond Club purchase**

![cluster_diamon](https://user-images.githubusercontent.com/5808185/36061736-8cae1920-0e84-11e8-995c-9b0ac5550f8e.png)

**Then we check for which cluster the purchase type is diamond | we see that Cluster 6 has the Prediction of Diamond Club purchase**

![cluster6](https://user-images.githubusercontent.com/5808185/36060318-32c67496-0e6d-11e8-96b7-1ce006c20a36.PNG)

**We extract all the values combination of games_before_purchase | balance_before_purchase in cluster 6**

![custer6](https://user-images.githubusercontent.com/5808185/36061685-c1eec270-0e83-11e8-8208-3c6c1405e7db.PNG)

**Now we check for our prediction and feed this combination in machine to check how true the different combination is performing**

![value_cus6](https://user-images.githubusercontent.com/5808185/36061703-fe7c2354-0e83-11e8-8a06-01d2b2e0f2ba.PNG)

#Hence this is the desire point in time when a we should push user a Diamond Club offer

![value_for_diamon](https://user-images.githubusercontent.com/5808185/36061818-31e4d536-0e86-11e8-9959-e097c04a5273.PNG)

##NOTE we should merge other cluster values which are aligned to the similar behavior of purchasing the diamond club

https://github.com/irfanalidv/UFL_London/blob/master/First_trans_Diamond_purchse.csv

**We have Decision Tree based Algorith for the above prediction**

![dtree](https://user-images.githubusercontent.com/5808185/36061199-fc88f984-0e7c-11e8-9638-328c4f26b343.png)

