# CouponRedemptionMateLabs
Problem Description:
● Certain organization's advancements are shared across different channels including
email, notices and so forth.
● Some of these campaigns incorporate coupon limits that are offered for a particular item
or scope of items.
● The retailer might want the capacity to anticipate whether clients recover the coupons
got across channels, which will help the retailer's advertising group to precisely plan
coupon builds, and grow progressively exact and focused on promoting techniques.
● The information accessible right now the beneath data, including the subtleties of an
example of: User demographics, Campaign and coupon details, Product details,
Previous transactions.
● In light of past exchange and execution information from the last 18 campaigns, the
candidates were suggested to anticipate the probability of a coupon being reclaimed
on the proper validation cut that should be made.
Data Description:
● Train : Contains the coupons offered to the given customers under 18 campaigns.
● Campaign Data : Campaign info for each of the 18 campaigns present in the train data.
● Coupon item mapping : Mapping of coupon and items valid for discount under that
coupon.
● Customer demographics : Transaction data for all customers for the duration of
campaigns in the train data.
● Item Data : Item info for each item sold by retailer.
Summary:
● Customers get coupons under different campaigns and may decide to recover them.
● They can redeem the given coupon for any valid product for that coupon as per coupon
item mapping within the duration between camping start date and end date.
● Next, the customer will redeem the coupon for an item at the retailer store and that will
reflect in the transaction table in the column coupon_discount .
Evaluation Metric:
● The evaluation should be done on the validation slice that you’d create. The metric that
needs to be used is the ROC-AUC score.
