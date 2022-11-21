# machine_learning_trading_bot
# machine_learning_trading_bot
Upon preparing the data with dataoffset of 3 months and applied the data to SVM model. 
Considering the model to be a baseline model, the model's accuracy is 0.55.
The graph below points out how the model predicted compared to the actual returns. 
![Actual Vs Strategy Returns](https://github.com/kavuri-akhil/machine_learning_trading_bot/blob/0f3c1ce326b94408310570be977ab4e5a18f618a/baseline_actual_vs_strategic.png)

I later applied the model with the preprocessed data to Adaboost classification model which gave the best accuracy of 0.55 and the below graph points out the comparasion between Actual vs Strategy model.

![Comparision of Actual vs Strategic Returns using Adaboost Model](https://github.com/kavuri-akhil/machine_learning_trading_bot/blob/7cef13595a8ca3b6d7c8145c9595b2e8cc85d7f7/actual_vs_predicted.png)

The same model has been trained on preprocessed data with a dateoffset of 6 months and the model have given an accuracy of 0.53 where as the svm model predicted the returns with an accuracy of 0.56.
The graph comparing the predictions of actual vs strategy predictions using ada boost classifier with an dateoffset of 6 months. 

![Comparision of Actual Vs Strategic Returns with dateoffset of 6 months](https://github.com/kavuri-akhil/machine_learning_trading_bot/blob/efaf2555ac84f0d283d5a55f1a521505155d5dbd/Actual_vs_strategy_6month_LR.png)

The data is preprocessed again with date offset specified to 12 months and trained the Ada Boost Classifier model which gave the best accuracy score of 0.49. The graph comparing the actual vs predicted returns with date offset set to 12 months. 

![Comparision between Actual and Predicted Returns with dataoffset of 12 months](https://github.com/kavuri-akhil/machine_learning_trading_bot/blob/118bffce15e331e5d23de387a6e799c84b335fd7/act_vs_pred_12_months.png)

As a conclusion we can suggest that the greater the size of the data set doesn't imply that the model's accuracy is increased. 
