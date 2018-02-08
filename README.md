# UFL_London
Customer Intelligent from scratch

- What is the day since registering that a user typically purchases a first bundle?

![days_diff1](https://user-images.githubusercontent.com/5808185/35792832-0c91757e-0a75-11e8-8226-01e4f28fc0d5.PNG)

{ NOTE: we can see that most of the customers are leaving within 10 days from registration ]

![days_of_first_trans](https://user-images.githubusercontent.com/5808185/35792774-c0e56dec-0a74-11e8-9861-282d4c0c9e74.PNG)


**Center_days_around_different days for transaction** [NOTE : this is the center of cluster/group of days people have preference of doing the transaction ]

![first_day_center](https://user-images.githubusercontent.com/5808185/35806640-367e412e-0aa6-11e8-918b-947d42a30d46.PNG)

- Which bundle do they usually first purchase? 

**#transaction_iap_First_Purchase =28465 customers vs #transaction_iap_overall_purchase = 61852 customers**

**Transcation = 46.02115 % | revenue = 45.51897 %** 

 **#transaction_diamond_First_purchase =125 customers vs #transaction_diamond_overall_purchase = 930 customers**
 **Transcation = 13.4408602% | revenue = 13.44086 %**
 
**No_games_played_before_iap_purchase**

![no_game_iap_1st_pur](https://user-images.githubusercontent.com/5808185/35796671-4c5084bc-0a83-11e8-9b6d-d60ce87f7431.PNG)


Is there a correlation here with number of games they have played or their coin balance at   time of purchase?

![cor_plot](https://user-images.githubusercontent.com/5808185/35807923-34fc04c2-0aaa-11e8-8285-82a04a1376eb.png)

[ NOTE : No of games played is highly co-related ]

- What is the frequency of spenders in how often they make a purchase?

**Cus_days_of_association_VS_Total_Transaction** [NOTE : this helps us to understand the associations between users and there purchase
]

![cus_days_of_association_vs_total_transaction](https://user-images.githubusercontent.com/5808185/35808763-dc03b9de-0aac-11e8-9127-0a9dc7914644.png)

![freq_of_purch](https://user-images.githubusercontent.com/5808185/35794316-46e1aaf4-0a7b-11e8-88e4-08f012fd53a0.PNG)

**Weekly purchase frequency**

[NOTE :we can understand the weekly frequency purchase behavior of a user as how often they would do the transaction in a week or more]

![fre_weekly](https://user-images.githubusercontent.com/5808185/35795776-424b7d4e-0a80-11e8-9346-e1922c5f2076.PNG)

Are there any patterns here?

**Understanding pattern of transaction**
[NOTE: This is to help us understand the pattern of transaction changing over time.Since data is complex we can see from other dimension which would make more sense ]

![first_transa](https://user-images.githubusercontent.com/5808185/35811851-8dca171e-0ab5-11e8-9c9e-ca0cfcb0acd3.PNG)

[ NOTE: In the below graph we can understand the most of our transaction is happening within 3k balance to 700 games played | we can also see that blue dot sometime after having high balance people are rarely preferring to buy diamond purchase]

![first_trans_both](https://user-images.githubusercontent.com/5808185/35803664-a420d91e-0a9a-11e8-9fd5-7d5b1687a19c.PNG)

[NOTE : The graph below can help us give the purchase behavior over time ]

![overtime_transaction](https://user-images.githubusercontent.com/5808185/35801927-2711b5e8-0a94-11e8-9d26-363e61920b46.PNG)

**Monthly_transaction Pattern**
[NOTE : This is to help us understand the customer engagement monthly when they do most of the transaction mostly on weekends and there are also few month when we have high engagement of customers with respect to purchase eg June 2016, and also least engaged month May 2015-Dec2015 and so on with help of the visualization ]

![monthly_transaction](https://user-images.githubusercontent.com/5808185/35805002-137790b4-0aa0-11e8-95fb-e10a3e15fae9.png)

![monthly_transaction1](https://user-images.githubusercontent.com/5808185/35805003-13c3824e-0aa0-11e8-86c6-168c9e860123.png)

**Monthly revenue Pattern**
[NOTE: similarly, the below graph help us to understand in which month we make more cash equivalence and when people are doing high transaction values eg.Sep-Oct2016 we make more and there is also month when we don't have much of revenue eg June-July2017 and more]

![revnue](https://user-images.githubusercontent.com/5808185/35805092-8526f13c-0aa0-11e8-8d5f-1860d0896ac2.png)

![revnue1](https://user-images.githubusercontent.com/5808185/35805140-b925a596-0aa0-11e8-8457-ee7f695a6f6c.png)

**Overall_Buy_till_you_Die**

[NOTE : this can help us to understand which user is doing high transaction value, we can push offers, or more referral of users as they are most influenced played we can also recommend the other users who may like to reach to goal as the top players and compete against the best in the scoreboard]

![over_all_cus](https://user-images.githubusercontent.com/5808185/35805428-d5716612-0aa1-11e8-9422-62971e633b3e.PNG)

**Time_Series**
[NOTE : this was more of like my experiment to understand if users are buying high bundles after the time interval do they prefer to buy higher value of bundles In few month we don't get higher purchase bundle as the month starts after a week there is hike in purchase and continue till quarter of month most filled till mid to most ]

![time_series](https://user-images.githubusercontent.com/5808185/35804701-d71d044c-0a9e-11e8-99f2-199b4f28c718.PNG)

- At what point do spenders stop paying?

**Last_Days_association** [NOTE : we can see that most of the customers are leaving within 10 days ]

![days_last](https://user-images.githubusercontent.com/5808185/35810147-bcf6f160-0ab0-11e8-8067-9bdd741237fb.PNG)

![last_day](https://user-images.githubusercontent.com/5808185/35807154-eec98b5c-0aa7-11e8-8812-92f733392e18.PNG)

**Center_days_value_around_which_days_varies** [NOTE : This is the center of cluster/group of days people have preference of doing there last transaction]

![last_day_cet](https://user-images.githubusercontent.com/5808185/35807225-2457ad76-0aa8-11e8-99f3-a9f797aa7c47.PNG)


- Is there a pattern that drives those users who purchase the more expensive coin bundles?
[NOTE : High game value leads to getting coin bundle purchase | we can see the yellow bubble can size resembles the bundle size]
**First_transaction_Coin_games_balance**

![first_transaction_scatter_plot_size coins](https://user-images.githubusercontent.com/5808185/35807675-732db1a6-0aa9-11e8-8dbd-35fd068d3c7a.png)

**Time_taken_for_2nd_transaction** [NOTE : as we analyze the 1st transaction we can do for 2nd and 3rd and so on as per our interest on an average people have 4 transactions the last transaction]

![2nd_tran](https://user-images.githubusercontent.com/5808185/35811025-812b8238-0ab3-11e8-974d-80bd5717df2e.PNG)

![center_2nd_trans](https://user-images.githubusercontent.com/5808185/35811026-81839892-0ab3-11e8-9a53-3577b546983e.PNG)

![days_2nd_trans](https://user-images.githubusercontent.com/5808185/35811024-80e01168-0ab3-11e8-87c7-2a0ed12df864.PNG)


**Possible driven transaction combination for First transaction**
[NOTE : This can help us to understand riving factor of combination of transaction people would do as e cluster all the transaction with most influenced number in the overall transaction as we get this values which is help us understand when people would do trsanction]

![purchase_combo](https://user-images.githubusercontent.com/5808185/35803293-44f6e9e8-0a99-11e8-9942-fc63ae032aaf.PNG)

[NOTE : we see the above combination of the dataset for the values of games and balance, the below graph help us to understand the category of customer we fall in such combination.]

![combination](https://user-images.githubusercontent.com/5808185/35803410-c204f07e-0a99-11e8-8db7-eb7e9b0d0dab.png)


**Predictive model for purchase classification**
[NOTE : This is predictive model to classify upcoming customers what would be there first purchase when they reach certain combination of games played and balance with 94% accuracy we can understand what would be they buying and can push offer some sort of another way to bind them to do the transaction]

![predictive_model_1](https://user-images.githubusercontent.com/5808185/35803101-95e88b64-0a98-11e8-8953-57361fe8030e.PNG)

