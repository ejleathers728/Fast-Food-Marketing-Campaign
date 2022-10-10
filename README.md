# Fast-Food-Marketing-Campaign

Data Set: Fast Food Marketing Campaign A/B Test
https://www.kaggle.com/datasets/chebotinaa/fast-food-marketing-campaign-ab-test

Scenario: A fast-food chain plans to add a new item to its menu. However, they are still undecided between three possible marketing 
campaigns for promoting the new product. In order to determine which promotion has the greatest effect on sales, the new item is introduced 
at locations in several randomly selected markets. A different promotion is used at each location, and the weekly sales of the new item are 
recorded for the first four weeks.

Dataset Info:
MarketID: unique identifier for market
MarketSize: size of market area by sales
LocationID: unique identifier for store location
AgeOfStore: age of store in years
Promotion: one of three promotions that were tested
week: one of four weeks when the promotions were run
SalesInThousands: sales amount for a specific LocationID, Promotion, and week

The purpose of this project was to deepen software knowledge of SQL and Tableau with a marketing dataset. For that reason this analysis 
focused on descriptive statistics when evaluating which marketing campaign the fast-food chain should use when hard launching the new menu 
item nationally. 

It should be noted that an A/B test or multivariate test is recommend to prove the statistical significance of the campaign of your choice. 
However, with the limited data, and softwares of choice for the project, promotion success will be determined based on the sales in the four 
week testing period. 

**Preliminary Findings:**

Respectively promotions one and three appear to compete equally across all markets with promotion two consistently peforming with lower sales.

The age of the store did not appear to play a role in the performance of the promotions. However, the age of the store did have an impact on 
overall sales in the four week period in general. With stores in the first five years accounting for the highest overall and average sales 
and decreasing as the store gets older.  A possible explanation for this could be that the locations still have hype around them - especially 
if it’s the first of its kind in that market. Think In-n-out or Raising Caines building in a state that has never had one before. The hype 
around it despite any marketing efforts will most likely remain consistent for the first few years and dwindle down as more locations are 
likely built in the area.

Ultimately, it is recommended to continue the launch with promotion one and/or three. 

**Future tests:**
In an ideal scenario, you would have more marketing specific data (in respect to the channels used) to aid in the measurement of success, 
such as impressions, engagement, click through rate, open rate, conversion rate etc. Combining this data with the sales data opens a new 
scope of questions. For instance, going along with the above scenario, if promotion two was outperforming according to traditional digital 
marketing metrics but wasn’t producing any sales that could be evidence that there is a disconnect with the materials and the product or that 
the brand is talking to the wrong segment. Either way, it helps you learn not only that it isn’t performing but also the low performance can 
be improved for the future.
