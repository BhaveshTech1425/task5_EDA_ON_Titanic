# task5_EDA_ON_Titanic

The EDA on the synthetic Titanic dataset (big_titanic.csv, 10,000 rows) revealed the following insights:

Survival Rate: Approximately 37% of passengers survived. The dataset exhibits a realistic class imbalance.


Class & Survival:

1st class passengers had significantly higher survival rates.

3rd class passengers had the lowest survival rate.

Socioeconomic status played a crucial role in survival chances.


Gender Distribution:

The dataset was male-dominated (~65% male).

Survival probability is expected to favor females based on historical trends, though this should be validated in modeling.


Age:

Most passengers were between 20–40 years old.

The age distribution was fairly normal, with a slight right skew.

Younger passengers had slightly better survival odds.


Fare:

Survivors tended to have paid higher fares.

Fare is positively correlated with survival, and outliers suggest wealthy individuals were more likely in 1st class.


Family Features (SibSp & Parch):

Passengers with small families (1–2 members) had better survival rates than those with larger families or none.


Embarkation Point:

Most passengers boarded from port 'S' (Southampton), but survival varied across ports, with those from 'C' having better outcomes.


Correlation Insights:

Fare and Pclass showed the strongest correlations with survival.

Other features like Age, SibSp, and Parch had weaker relationships.
