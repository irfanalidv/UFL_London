## UFL London: Customer Intelligence from Scratch

### When do users typically purchase their first bundle?

The majority of customers tend to make their first bundle purchase within the first 10 days of registration. This is evident from the following visualizations:

- **Days Since Registration to First Purchase:** Most users make their first purchase within 10 days.
![days_diff1](https://user-images.githubusercontent.com/5808185/35792832-0c91757e-0a75-11e8-8226-01e4f28fc0d5.PNG)

- **First Transaction Centered Around Different Days:** This shows the clustering of days around the preferred transaction time.
![first_day_center](https://user-images.githubusercontent.com/5808185/35806640-367e412e-0aa6-11e8-918b-947d42a30d46.PNG)

### Which bundle do they usually purchase first?

- **In-App Purchase (IAP):** 28,465 customers made their first purchase with an IAP bundle, accounting for 46.02% of transactions and 45.52% of revenue.
- **Diamond Purchase:** 125 customers made their first purchase with a diamond bundle, accounting for 13.44% of transactions and revenue.

![no_game_iap_1st_pur](https://user-images.githubusercontent.com/5808185/35796671-4c5084bc-0a83-11e8-9b6d-d60ce87f7431.PNG)

### Correlation between games played or coin balance at purchase time

There is a strong correlation between the number of games played and the likelihood of making a purchase. The coin balance at the time of purchase also plays a significant role, but it is less influential than the number of games played.

![cor_plot](https://user-images.githubusercontent.com/5808185/35807923-34fc04c2-0aaa-11e8-8285-82a04a1376eb.png)

### Frequency of purchases

- **Customer Association vs. Total Transactions:** This helps understand the relationship between the length of customer association and their total number of transactions.
![cus_days_of_association_vs_total_transaction](https://user-images.githubusercontent.com/5808185/35808763-dc03b9de-0aac-11e8-9127-0a9dc7914644.png)

- **Weekly Purchase Frequency:** Shows how often users make purchases within a week or more.
![fre_weekly](https://user-images.githubusercontent.com/5808185/35795776-424b7d4e-0a80-11e8-9346-e1922c5f2076.PNG)

### Patterns in transaction behavior

- **Transaction Patterns Over Time:** Most transactions occur when users have a balance between 3000 coins and have played up to 700 games. Users rarely purchase diamonds even when they have a high balance.
![first_transa](https://user-images.githubusercontent.com/5808185/35811851-8dca171e-0ab5-11e8-9c9e-ca0cfcb0acd3.PNG)
![first_trans_both](https://user-images.githubusercontent.com/5808185/35803664-a420d91e-0a9a-11e8-9fd5-7d5b1687a19c.PNG)

- **Monthly Transaction and Revenue Patterns:** High engagement and revenue are observed in certain months, such as June 2016 and September-October 2016. Low engagement months include May 2015-December 2015.
![monthly_transaction](https://user-images.githubusercontent.com/5808185/35805002-137790b4-0aa0-11e8-95fb-e10a3e15fae9.png)
![revnue](https://user-images.githubusercontent.com/5808185/35805092-8526f13c-0aa0-11e8-8d5f-1860d0896ac2.png)

### When do spenders stop paying?

- **Last Days of Association:** Most customers leave within 10 days.
![days_last](https://user-images.githubusercontent.com/5808185/35810147-bcf6f160-0ab0-11e8-8067-9bdd741237fb.PNG)

- **Center of Last Transaction Days:** Clustering shows a preference for the last transaction timing.
![last_day_cet](https://user-images.githubusercontent.com/5808185/35807225-2457ad76-0aa8-11e8-99f3-a9f797aa7c47.PNG)

### Patterns driving purchases of more expensive coin bundles

- **High Game Value:** Users with higher game values tend to purchase more expensive coin bundles. The yellow bubbles in the scatter plot indicate bundle sizes.
![first_transaction_scatter_plot_size coins](https://user-images.githubusercontent.com/5808185/35807675-732db1a6-0aa9-11e8-8dbd-35fd068d3c7a.png)

- **Time Taken for Second Transaction:** Users typically make a second transaction shortly after the first, indicating a pattern in purchasing behavior.
![2nd_tran](https://user-images.githubusercontent.com/5808185/35811025-812b8238-0ab3-11e8-974d-80bd5717df2e.PNG)

### Possible driven transaction combinations for the first transaction

Understanding the driving factors or combinations of transactions helps in predicting customer behavior and designing targeted offers.

![purchase_combo](https://user-images.githubusercontent.com/5808185/35803293-44f6e9e8-0a99-11e8-9942-fc63ae032aaf.PNG)

### Predictive model for purchase classification

A predictive model with 94% accuracy can classify upcoming customers' first purchase based on their games played and balance. This helps in pushing offers and binding customers to make transactions.

![predictive_model_1](https://user-images.githubusercontent.com/5808185/35803101-95e88b64-0a98-11e8-8953-57361fe8030e.PNG)

By understanding these patterns and behaviors, we can better target our customers, improve engagement, and increase revenue.
