# BigMart-Sales-Prediction

BigMart Sales Prediction using Machine Learning and Deep Learning

This project focuses on predicting product sales in retail stores using machine learning and deep learning techniques. In retail businesses, poor demand forecasting can lead to overstocking, which increases storage cost, or understocking, which causes loss of sales. The main aim of this project is to predict Item Outlet Sales accurately and help improve decision making.

The dataset used is the BigMart Sales dataset from Kaggle, which contains around 8500 records with multiple features related to products and stores. The target variable is Item_Outlet_Sales. Important features include item type, item weight, item price, outlet size, and outlet type.

In the preprocessing stage, missing values in Item_Weight were filled using the mean, and missing values in Outlet_Size were filled using the mode. Outliers were removed using the IQR method to improve model performance. Unnecessary columns such as Item_Identifier and Outlet_Identifier were also removed.

Feature engineering was applied by creating a new feature called Item_Age using the outlet establishment year. The original year column was removed. Categorical variables were converted into numerical form using one-hot encoding.

Different machine learning models were used, including Linear Regression, Decision Tree, Random Forest, SVR, and KNN. Ensemble methods such as Random Forest, Gradient Boosting, and Stacking were also used to improve accuracy. In addition, deep learning models like ANN and DNN were implemented to capture complex patterns.

The dataset was split into training and testing sets using an 80:20 ratio. All models were evaluated using MAE, RMSE, R², and MAPE.

From the results, ensemble models performed better than individual models. Random Forest gave the best performance with higher accuracy and lower error. Deep learning models worked well but did not outperform Random Forest due to the smaller dataset size.

The project includes graphs such as model comparison, actual vs predicted values, stacking performance, and deep learning comparison. These help in understanding the results clearly.

To run the project, open the notebook file and execute all cells step by step. Make sure required libraries like pandas, numpy, matplotlib, seaborn, scikit-learn, and tensorflow are installed.

Overall, this project shows how machine learning and deep learning can be used for sales prediction and how ensemble models improve performance.
