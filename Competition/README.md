## Competition rules
### Teams
Teams should consist of 1-3 members. Please name the team - name will appear in the results table (can be anything you come up with but please avoid PII data in the group name e.g. surnames).

### Dataset and competition's goal
Goal of the competition is to achieve highest **[F1-score](https://en.wikipedia.org/wiki/F-score)** in classification of target variable **IsIPA**. To create a model please use **IPA.csv** dataset (used it for both train and validation dataset) and predict labels on **IPA_test.csv** data. Description of dataset features can be found in **IPA_description.txt**.

### Results delivery
Please send the results to _lkrain@sgh.waw.pl_. 

Deadlines: 
* Group 11 - 12:00 13.05.2022

In the e-mail please specify name of the group and members. Required attachments are:
1. R/Python/Julia/any-other-language script or notebook with used code
2. CSV file named **[group_name]_IPA_prediction.csv** with one column named **Prediction** containing 5000 predictions with values 1/0 or TRUE/FALSE for dataset **IPA_test.csv**. Please make sure predictions order is the same as rows in test data.  

Table with ranking will appear in this README file. Best team in each course group will receive 5 points, next 4 points, etc.

Good luck!

### Competition results

Group 11

| Team          | F1-score | Points | Language | Model                            |
|---------------|----------|--------|----------|----------------------------------|
| JK            | 78,63    | 5      | R        | Gradient Boosted Trees (XGBoost) |
| Grupa_SD      | 78,37    | 4      | Python   | Gradient Boosted Trees (XGBoost) |
| Python        | 78,07    | 3      | Python   | CART                             |
| TW            | 77,38    | 2      | Python   | Gradient Boosted Trees (XGBoost) |
| MiRaMi        | 68,81    | 1      | Python   | Logistic Regression              |
| Robot Chicken | 52,21    | 0      | R        | LDA                              |
| Penguins      | 33,91    | 0      | R        | Logistic Regression              |
