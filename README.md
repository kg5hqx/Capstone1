### Forecasting Pharmacy Medication Sales

**Karin Huegele**

#### Executive summary
This project explores several models to find the best model to forecast pharmacy medication sales.

#### Rationale
Accurate forecasting of drug sales will enable pharmacies to manage their inventory more efficiently. If pharmacies can rely on the forecast's accuracy, they can maintain smaller inventories, reduce operating costs, and reduce waste due to medication expiration.

#### Research Question
In the pharmacy industry, it is essential to ensure patient safety and that the pharmacy dispenses only high-quality medications. As the pharmacy mail order utilization increases, it becomes crucial that the pharmacy can deliver medications efficiently and on time.  

However, predicting medication dispensing can be tricky. Some of the main factors that affect a prescription order are:
* Doctor's approval
* Pharmacy benefit manager's (PBM) approval
* Product availability
* Product unbreakable unit of packaging
* Risk of medication stockpiling

Due to PHI restrictions, patient personal health data is not publicly available. Using only the pharmacy sales data available in the public domain, how might we devise an accurate forecast of medication demand in the future?


#### Data Sources
For this project, I use a dataset from Kaggle consisting of weekly pharmacy sale data collected in 6 years, from 2014 to 2019, for eight drug categories.

#### Methodology
I will perform a manual seasonal decomposition as my baseline for this project. From there, I will improve performance using ARMA, SARIMAX, and RNN models using Dense, Simple RNN, LSTM with one layer, and LSTM with two layers.

#### Results
So far, SARIMAX is performing the best.

#### Next steps
Continue to explore my models to see if I can improve them further.

#### Outline of project

- [[Link to notebook 1](https://github.com/kg5hqx/Capstone1/blob/master/notebook/Take-2-Module-20.ipynb)]
- [Link to notebook 2]()
- [Link to notebook 3]()


##### Contact and Further Information
For more information about this project, please contact Karin Huegele, kg5hqx@hugelheim.us
