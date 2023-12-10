# Consumer Behavior and Shopping Habits Research
Consumer Behavior and Shopping Habits Research with EDA and ML.\
Dataset was taken from [Kaggle]('https://www.kaggle.com/datasets/zeesolver/consumer-behavior-and-shopping-habits-dataset').

Beginning: 30 nov 2023\
End: 30 dec 2023

# Purpose
I want to create several ML models with different tasks. This dataset has no target value, so i will select it by myself or even create it. 

# Data
The column-wise description is down below:

**`Customer ID`**: A unique identifier assigned to each individual customer.\
**`Age`**: The age of the customer.\
**`Gender`**: The gender identification of the customer.\
**`Item Purchased`**: The specific product or item selected by the customer during the transaction.\
**`Category`**: The broad classification or group to which the purchased item belongs.\
**`Purchase Amount (USD)`**: The monetary value of the transaction, denoted in United States Dollars (USD).\
**`Location`**: The geographical location where the purchase was made.\
**`Size`**: The size specification (if applicable) of the purchased item.\
**`Color`**: The color variant or choice associated with the purchased item.\
**`Season`**: The seasonal relevance of the purchased item.\
**`Review Rating`**: A numerical or qualitative assessment provided by the customer regarding their satisfaction with the purchased item.\
**`Subscription Status`**: Indicates whether the customer has opted for a subscription service.\
**`Shipping Type`**: Specifies the method used to deliver the purchased item.\
**`Discount Applied`**: Indicates if any promotional discounts were applied to the purchase.\
**`Promo Code Used`**: Notes whether a promotional code or coupon was utilized during the transaction.\
**`Previous Purchases`**: Provides information on the number or frequency of prior purchases made by the customer.\
**`Payment Method`**: Specifies the mode of payment employed by the customer.\
**`Frequency of Purchases`**: Indicates how often the customer engages in purchasing activities.

# Tasks
I selected 3 targets for 3 tasks:
* *REGRESSION*: predict **Purchase Amount** to find out, which clients are ready to spent more money.
* *CLASSIFICATION*: predict **Subscription Status** to fing out the loyalty of clients.
* *CLUSTERING*: predict **Frequency of Purchases** to define groups of clients depending on how often they make purchases.