# NASA-Turbofan-Predictive-Maintenance

**🔑 KEY NOTE: please read this**

*some graphs in the notebook are not rendered by Github since the frame amount exceeded*

inorder to view the full notebook please click this -> [Notebook](https://nbviewer.jupyter.org/github/sashank24/NASA-Turbofan-Predictive-Maintenance/blob/main/notebook/NASA_Turbo_Engine_RUL.ipynb) (📍wait for it load...)

*if the above method doesn't work TRY THIS* -> copy paste this link https://github.com/sashank24/NASA-Turbofan-Predictive-Maintenance/tree/main/notebook in this [nbviewer.jupyter.org](https://nbviewer.jupyter.org/) website and click the file with the '.ipynb' extension and wait for it to render (takes about 10 seconds) 

* created a model which can be used as a tool that estimates the RUL(remaining useful life) of an engine.
* Achieved an **ACCURACY OF 98%**
* This model predicts the RUL of an engine and Outputs the value 1 or 0 
* '1' meaning that the engine is nearing its repair time, Hence it needs a check and '0' meaning safe to proceed
* Features Engineered from the Cycle and generated new variable to label the engine 
* Visualized Advanced graphs and traces using plotly
* Used lightgbm and xgboost libraries for efficient model building
* Used RandomizedSearchCV to optimize the classification models hypertuned the parameters to get the best-fitting model
* The pickled model can be used by anyone, it can be found **in the model directory of the main branch**

## Description of code and resources used in this project
** Python version:** 3.8
** Packages:** pandas, numpy, seaborn, matplotlib, plotly, sklearn, lightgbm, xgboost, pickle

** Link for the dataset -> [NASA_Turbofan_RUL_Dataset](https://www.kaggle.com/darkside92/turbofan-predictive-maintenance-nasa)

## Why a solution based on *Machine Learning* is needed for predictive maintenance of heavy machinery?

Major Advantages on incorporating Machine Learning in Predective maintenance are:

*         Can cut Cost by a huge margin
*         Safety purposes (Varies according to the field in use)
*         Saves Time 
*         Repair cost is considerably reduced
*         Better planning of Machine usage
*         Prevents major damages to Machine
