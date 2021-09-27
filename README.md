# aryaai

File structure:

  1.THe above notebook consist of feature exploration and analysis and model developemnt process
  2.test_pred.csv containig the result of test data
  3.result.py prints the validation result using saved xgboost model
  4.xgb_model is the saved model


conclusion:

  1. The data was skwed data towards 0 having no linear corelation wrt to target
  2. The data was wasn't having any high corelation no big corelation wrt to target or with each other(features)
  3. The XGB probabilty based model was choose for such data because of XGBoost capability of forming boosting trees supporiting weak leraners
  4. The propabilty scores were having clear sepration with 0.5 as threshold betweeen 1 and 0
  5. The F1 score for the validation data set was 90 and 91 from training data

