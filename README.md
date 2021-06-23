# Chennai-Housing-Price-Prediction
## Business Task
To analyse Chennai Housing Price Dataset and predict the cost price of various houses.
## Business Objective
1. What factors contribute to a costly selling price.
2. Which area in chennai is the cheapest to buy a house.
3. Build a Machine Learning model to predict the housing prices.
## Dataset Used
Chennai Housing Price dataset contains the following attribute:-
1. PRT_ID	: object
2. AREA	17: object
3. INT_SQFT: int64
4. DIST_MAINROAD: int64
5. N_BEDROOM: float64
6. N_BATHROOM: float64
7. N_ROOM:	int64
8. SALE_COND:	object
9. PARK_FACIL: object
10. BUILDTYPE:	object
11. UTILITY_AVAIL:	object
12. STREET:	object
13. MZZONE:	object
14. QS_ROOMS:	float64
15. QS_BATHROOM:	float64
16. QS_BEDROOM:	float64
17. QS_OVERALL:	float64
18. COMMIS:	int64
19. SALES_PRICE: int64<br>
This dataset contains 7109 housing data and 19 columns.<br>
## Analysis
1. sqfeet area and the price of house are linearly correlated to eachother.
2. The price of house and the commission that the broker asks are also correlated.
3. Family Land has more mean distance from main road which is a good thing.
4. Parking Facility is equally distributed in all the areas and buildtype in chennai.
5. Karrapakkam, Adayar and chrompet have low sales( low sqfeet ) price and the rest have a high sale price( high sqfeet).
## Machine Learning Models used
1. linear_reggression:<br>
Score=0.954449 , Best Params={'normalize': False}<br>
2. lasso:<br>
Score=0.954449	, Best Params={'alpha': 2, 'selection': 'random'}<br>
3. decision_tree:<br>
Score=0.970032 , Best Params={'criterion': 'friedman_mse', 'splitter': 'random'}<br>
