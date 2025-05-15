## Predicting Competitive eBay Auctions Using Bagging, Random Forests, and Boosting
On eBay, not all auctions attract multiple bidders. Sellers want to know in advance whether their auction listing will become "competitive" — i.e., attract at least two bids. By predicting this, sellers and the platform can adjust auction settings to increase engagement and revenue.

### Objective
Build and compare three ensemble models, **Bagging, Random Forests, and Boosting**, to predict whether an auction will be competitive (```Competitive.``` = 1) based on item, seller, and auction characteristics.ing

### Dataset
- **File:** eBayAuctions-lab14.csv
- **Observations:** 1,972 auctions (May–June 2004)
- **Target Variable:** ```Competitive.``` (1 = ≥2 bids, 0 = <2 bids)

### Techniques
- Data preprocessing & feature engineering
- Train/test split
- Model training: Bagging, Random Forest, Boosting
- Evaluation: Accuracy, Confusion Matrix, ROC Curve
- Feature importance visualization

### Modeling Workflow
#### 1. Converting numeric variables to categorical variables
#### 2. Bagging
- Trained a **bagging model** using all available predictors
- Generated predictions on the dataset
- Evaluated performance using a confusion matrix
#### 3. Random Forests
- Trained a random forest model with tuned mtry value
- Visualized feature importance using variable importance plot
- Predicted outcomes on the dataset
- Assessed classification accuracy via confusion matrix

### Business Takeaways
- Opening price and seller rating are critical to auction success
- Auctions that end mid-week (e.g., Wednesday) tend to be more competitive
- Sellers can optimize auction parameters (e.g., pricing and end day) to increase bidding activity
