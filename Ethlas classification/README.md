### Background:
- In the wallet dataset, we are given 35 features and would have to predict whether the address would be blacklisted.
- To do this, we first ask 2 questions:
    1. minimum of 10 transaction level features based on relative importance that will help us answer that question
    2.  Given the features, output a prediction score as to whether the wallet would be good or bad

### strat:
- do data cleaning
- feature engineering/selection (use Standardization)
- use train test split
- train using log reg (use advanced strategies after some iterations)
- create a case study for one potential wallet address and transaction details (one datapoint)
- do post-analysis for qn 1 and 2