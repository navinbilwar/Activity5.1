The objective of this code is to distinguish between customers who accepted a driving coupon versus those that did not for various coupon types.
The code in the notebook has been used to analyze two coupon types - Bar and $20-$50 restaurant category.

Link to notebook: https://github.com/navinbilwar/Activity5.1/blob/main/prompt.ipynb

<b>Analysis of Bar coupon:</b>

1. Amongst all coupon categories, the overall acceptance rate for bar coupons was lowest: 41%

2. Coupon acceptance based on number of bar visits per month:<br>
a) Acceptance rate of those who went to bar 3 or fewer times a month: 64.74%<br>
b) Acceptance rate of those who went to bar 4 to 8 times a month: 78.0%<br>
c) Acceptance rate of those who went to bar more than 8 times a month: 73.47%<br>
d) Acceptance rate of those who went to bar 4 or more times a month: 76.88%<br>

3. Coupon acceptance based on age groups for those who went to bar at least once a month:<br>
a) Acceptance rate of those who went to bar more than once a month & over 25: 69.52%<br>
b) Acceptance rate of those who went to bar more than once a month & below 25: 67.05%<br> 

4. Higher acceptance rate categories:<br>
a) Acceptance rate of those who went to bar more than once a month, passengers that were not a kid and with occupations other than farming, fishing, forestry: 71.79%<br>
b) Acceptance rate of those who went to bar more than once a month, passengers that were not a kid and were not widowed: 71.79%<br>
c) Acceptance rate of those who went to bar more than once a month and under 30: 72.17%<br>

5. Lower acceptance rate category:<br>
Acceptance rate of those who went to cheap restaurants more than 4 times a month and income under 50k: 45.35%<br>

Key highlights:
1. Bar coupons acceptance was less (45.35%) by people who went to cheap restaurants more than 4 times a month and whose income was less than 50k. 
2. The coupon acceptance was higher for other categories analyzed above with highest (78%) being by those who went to bar 4 to 8 times a month or by those who went to bar more than once a month and under the age of 30 (72.17%)
3. Also, those who went to bar more than once a month and not traveling with kids had higher coupon acceptance rate (71.79%).
<br>
<b>Analysis of expensive restaurant coupon - Restaurant(20-50):</b>

1. Amongst all coupon categories, the overall acceptance rate for bar coupons was lowest (41%), followed by expensive restaurant coupons (44.1%)

2. The acceptance rate of coupon is positively correlated with the # of visits per month:<br>
a) Acceptance rate of those who never went to a restaurant: 38.24%<br>
b) Acceptance rate of those who went to restaurant 3 or fewer times a month: 52.74%<br>
c) Acceptance rate of those who went to restaurant 4 to 8 times a month: 62.64%<br>
d) Acceptance rate of those who went to restaurant more than 8 times a month: 68.75%<br>

3. Analyzing coupon acceptance based solely on the age groups isn't very effective and was low when analyzed across different age groups.
However, the acceptance rate was higher when the drivers were not traveling alone.<br>
a) There wasn't any significant difference in the coupon acceptance rate for those who visit expensive restaurants more than once a 
  month when compared over age 25 (55.67%) and below age 25 (55.05%). However, when analyzed further by different age groups, it was highest for age 26 (65.09%).<br>
b) When drivers are not traveling alone, the coupon acceptance rate for expensive restaurants is much higher and for those who visit 
  expensive restaurant at least once a month. The mean acceptance rate across different age groups increased from 55.86% to 59.27% when not traveling alone.<br>

4. The coupon acceptance rate for males is higher (61.18%) than females (53.41%) for those who visit expensive restaurants at least once a month and when not traveling alone.

5. The expensive restaurant coupon acceptance rate increased for both males (63.16%) and females (55%) for those who also went to a coffee place at least once a month in 
addition to going to an expensive restaurant at least once a month and when not traveling alone.

6. For those who visit expensive restaurants at least once a month, the expensive restaurant coupon acceptance rate is highest when the coupons are sent earlier in the day, 
with 10am being the highest (78.57%) and the coupon acceptance goes down as the day progresses with 10 pm being the lowest (41.07%).
