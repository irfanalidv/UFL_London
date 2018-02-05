# UFL_London
Customer Intelligent from scratch

- What is the day since registering that a user typically purchases a first bundle?

![days_diff1](https://user-images.githubusercontent.com/5808185/35792832-0c91757e-0a75-11e8-8226-01e4f28fc0d5.PNG)


![days_of_first_trans](https://user-images.githubusercontent.com/5808185/35792774-c0e56dec-0a74-11e8-9861-282d4c0c9e74.PNG)

- Which bundle do they usually first purchase? 

#transaction_iap_First_Purchase =28465 customers vs #transaction_iap_overall_purchase = 61852 customers 

Transcation = 46.02115 % | revenue = 45.51897 % 

**No_games_played_before_iap_purchase**

![no_game_iap_1st_pur](https://user-images.githubusercontent.com/5808185/35796671-4c5084bc-0a83-11e8-9b6d-d60ce87f7431.PNG)

#transaction_diamond_First_purchase =125 customers vs #transaction_diamond_overall_purchase = 930 customers

Transcation = 13.4408602% | revenue = 13.44086 % 

Is there a correlation here with number of games they have played or their coin balance at   time of purchase?

- What is the frequency of spenders in how often they make a purchase? 
![freq_of_purch](https://user-images.githubusercontent.com/5808185/35794316-46e1aaf4-0a7b-11e8-88e4-08f012fd53a0.PNG)

**Weekly purchase frequency**

![fre_weekly](https://user-images.githubusercontent.com/5808185/35795776-424b7d4e-0a80-11e8-9346-e1922c5f2076.PNG)

Are there any patterns here?

- At what point do spenders stop paying?

- Is there a pattern that drives those users who purchase the more expensive coin bundles?

**Possible driven transaction combination for First transaction**

  games_before_purchase balance_before_purchase
1             25.283901               722.66533
2            374.555556             30764.00000
3            187.269231             17173.76923
4             13.477446               229.31500
5            127.232558              3506.30233
6             89.119403              9708.64179
7              9.191331                44.03603

![cluster_first_trans](https://user-images.githubusercontent.com/5808185/35801524-b5dd71f6-0a92-11e8-8a3f-0405e04f8fc0.png)
