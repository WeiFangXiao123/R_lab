## Predicting Competitive eBay Auctions Using Bagging, Random Forests, and Boosting
On eBay, not all auctions attract multiple bidders. Sellers want to know in advance whether their auction listing will become "competitive" — i.e., attract at least two bids. By predicting this, sellers and the platform can adjust auction settings to increase engagement and revenue.

### Objective
Build and compare three ensemble models, **Bagging, Random Forests, and Boosting**, to predict whether an auction will be competitive (```Competitive.``` = 1) based on item, seller, and auction characteristics.ing

### Dataset
- **File:** eBayAuctions-lab14.csv
- **Observations:** 1,972 auctions (May–June 2004)
- **Target Variable:** ```Competitive.``` (1 = ≥2 bids, 0 = <2 bids)
