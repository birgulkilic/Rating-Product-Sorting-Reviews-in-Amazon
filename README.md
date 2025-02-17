# Rating-Product-Sorting-Reviews-in-Amazon
![image](https://github.com/user-attachments/assets/d03b4f47-5535-4016-9e44-72879dbe9663)

#Business Problem
One important problem in e-commerce is the correct calculation of product ratings after sales. Solving this problem will provide more customer satisfaction on the e-commerce site, help sellers' products stand out, and ensure a smooth shopping experience for buyers. Another problem is the proper ranking of product reviews. Misleading reviews can directly affect a product's sales, causing both product loss and customer dissatisfaction. Solving these two main problems will help e-commerce sites and sellers increase their sales while allowing customers to complete their shopping journey smoothly.

#Dataset Story
This dataset contains product data from Amazon, including product categories and various metadata. It includes user ratings and reviews for the product with the most reviews in the Electronics category.

Variables:

-reviewerID: User ID

-asin: Product ID

-reviewerName: User Name

-helpful: Helpful review rating

-reviewText: Review text

-overall: Product rating

-summary: Review summary

-unixReviewTime: Review time (Unix format)

-reviewTime: Raw review time

-day_diff: Number of days since the review

-helpful_yes: Number of helpful votes for the review

-total_vote: Total votes for the review

In the shared dataset, users have given ratings and written reviews for a product. The goal of this task is to evaluate the ratings by weighting them according to the date. The weighted rating should be compared with the initial average rating.

Step 1: Calculate the average rating of the product.

Step 2: Calculate the weighted average rating based on the date.

Step 3: Compare the average rating of each time period in the weighted rating.
