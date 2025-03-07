# ml_cupon
 Amazon Cupon Analysis
 
Summary:
 
Amazon Coupon Targeting Analysis

This analysis presents data-driven insights to determine the ideal customer segments for coupon distribution. We evaluated six key dimensions—Education, Income, Marital Status, Occupation, Age, and Delivery Time, to guide targeted coupon strategies.

Approach:

We examined acceptance rate heatmaps for each coupon type across the six dimensions. For each coupon, the highest acceptance rate category was selected per dimension. This method ensured that our recommendations reflect the segments most likely to engage with the coupon offer.

Ideal Customer Profiles by Coupon Type:

Bar Coupon: The highest acceptance criteria describes the customers who have Some High School education (78.57%), are Single (54.61%), around 21 years of age (50.60%), and work in Architecture & Engineering field (66.67%) with income abouve $100k (47.42%). Their coupons should be delivered at 6PM.

Carry out & Take away Coupon: Ideal customers show Some High School education (93.75%), are Widowed (84.62%), and work in Building & Grounds Cleaning & Maintenance profession (100.00%). Targeting is reinforced by an income range of 37,499 (77.49%), and age of 50plus (77.46%). The coupon should be delivered around 2PM.

Coffee House Coupon: The optimal segment includes customers with Some High School education (60.71%), who are Divorced (52.32%), are Healthcare Practitioners & Technical professionals (74.32%) with income of 99,999 (55.72%) or age below 21 (69.68%). Coupons should be delivered at 10AM.

Restaurant(20-50) Coupon: The best target is customers with Some High School education (58.33%), who are Unmarried (48.91%), and work in Healthcare Support (65.62%). Coupons are best delivered at 10AM, with additional factors including income of 37,499 (51.10%) and age of 26 (49.66%).

Restaurant(<20) Coupon: The data indicates that ideal customers have Some college with no degree (74.22%), are Single (72.99%), and work in Protective Service (89.47%). Their coupon should be delivered at 6PM, complemented by income levels of 62,499 (78.25%) and age of 46 (75.68%).
 
 
 
Project Context:

Imagine driving through town and a coupon is delivered to your cell phone for a restaurant near where you are driving. Would you accept that coupon and take a short detour to the restaurant? Would you accept the coupon but use it on a subsequent trip? Would you ignore the coupon entirely? What if the coupon was for a bar instead of a restaurant? What about a coffee house? Would you accept a bar coupon with a minor passenger in the car? What about if it was just you and your partner in the car? Would weather impact the rate of acceptance? What about the time of day?

Obviously, proximity to the business is a factor on whether the coupon is delivered to the driver or not, but what are the factors that determine whether a driver accepts the coupon once it is delivered to them? How would you determine whether a driver is likely to accept a coupon?

Overview:

The goal of this project is to use what you know about visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those that did not.

Data:

This data comes to us from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios including the destination, current time, weather, passenger, etc., and then ask the person whether he will accept the coupon if he is the driver. Answers that the user will drive there ‘right away’ or ‘later before the coupon expires’ are labeled as ‘Y = 1’ and answers ‘no, I do not want the coupon’ are labeled as ‘Y = 0’. There are five different types of coupons -- less expensive restaurants (under $20), coffee houses, carry out & take away, bar, and more expensive restaurants ($20 - $50).


