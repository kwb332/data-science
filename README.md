OVERVIEW

This Data Science Analysis seeks to answer the question, “Will a customer accept the coupon?” The goal is to distinguish between customers who accepted a driving coupon versus those that did not. 

The data used for this analysis comes from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios, including the destination, current time, weather, passenger, etc., and then asks people whether they will accept the coupon if they are the driver. Answers given that the users will drive there “right away” or “later before the coupon expires” are labeled as “Y = 1”, and answers “no, I do not want the coupon” are labeled as “Y = 0”. There are five different types of coupons—less expensive restaurants (under $20), coffee houses, carry out and take away, bars, and more expensive restaurants ($20–$50).

FINDINGS

(See Coupon.docx for readme with graphs on the findings.  Below is a summary of the same information so it has less details.)

Coupons from Coffee Houses were the most accepted.  This was followed closely by restaurants that cost less than 20 dollars.  This is consistent with what you would expect, since travelers may want to stop for coffee to keep themselves awake.  Also, as with everything else, price plays a huge factor on demand, the cheaper restaurant seemed to have more accepted coupons.  Interestingly enough, the most rejected coupons were the ones for the bar, this may be to avoid DUIs:

The hotter the temperature, the more likely coupons were accepted.  This may make sense because the sunny weather may be more conducive to taking a break at a restaurant patio or outside somewhere.


41% of bar coupons were accepted. According to the data, the more frequently an individual went to the bar each month, the less likely they were to accept bar coupons:  This trend seems to be consistent across age groups, less bar goers of all age purchased bar coupons.  It may be that bar goers limit going to the bar when on the road if they already go to the bar other times.  It is possible that people have their preferred bars that they like to go to and so the coupons are not incentive enough because they are not offered for their favorite bars.  It seems that, if the drivers were from sales related jobs or unemployed, and were alone in the car they were more likely to use the coupons.  In general, being alone in the car increased the likelihood of coupon usage across all occupations and age groups. People with partners were less likely to use the coupons.  The profession that was least likely to use the coupons were Architects and Engineers. 
Single people were more likely to use the coupons, if they were alone in the car.  The least likely individuals to use the coupon were people who had a partner as a passenger and were single.  Across all marital statuses, people who did not have passengers were most likely to use a coupon.

For people making incomes between 37,500 and 49,9000, there seems to be a negative correlation between the coupon acceptance and the frequency of going to cheap restaurants:  This may be due to people who go to cheap restaurants not having enough additional money to spend when on the road, even if they have a coupon.

 
