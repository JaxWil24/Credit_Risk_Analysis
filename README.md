# Credit Risk Analysis

## Overview
* Evaluating credit card risk using unbalanced classification. Parsing through the data, pulling together the valuable information associated with risk, and training the models. 

## Results
* Random Oversampler
	* The balanced accuracy score is 0.66, so the predictions are over 60% accurate.
  ![Balanced Accuracy-RandOverSample](https://user-images.githubusercontent.com/106329824/194069397-6762590f-3da9-41ac-811b-4ca73f1a4c67.png)

  * The precision is 0.99, so the correct positive predictions are 99% accurate compared to the total positive predictions.
  ![Report-RandOverSamplePre](https://user-images.githubusercontent.com/106329824/194072635-2d0b4674-2783-4700-a823-47b557aa0f3f.png)

  * The recall is 0.6, so the correct positive predictions are 60% accurate compared to the total actual positive predictions.
  ![Report-RandOverSampleRec](https://user-images.githubusercontent.com/106329824/194072603-acddc782-1ab2-430b-9ef0-3d0dcd0ea569.png)

* SMOTE
	* The balanced accuracy score is 0.64, so the predictions are over 60% accurate.
  
  ![Balanced Accuracy-SMOTE](https://user-images.githubusercontent.com/106329824/194073419-0ed8f0c4-d432-4df2-9c15-d2cb49ae1716.png)


  * The precision is 0.99, so the correct positive predictions are 99% accurate compared to the total positive predictions.
  ![Report-SMOTEPre](https://user-images.githubusercontent.com/106329824/194072788-06b4a4d9-b0a2-4ebc-95de-999259b57ab3.png)

  * The recall is 0.58, so the correct positive predictions are 58% accurate compared to the total actual positive predictions.
  ![Report-SMOTERec](https://user-images.githubusercontent.com/106329824/194072804-d3e70386-c83f-4d73-83c3-e812fd5f9070.png)


* ClusterCentroids
  * The balanced accuracy score is 0.54, so the predictions are over 50% accurate.
  ![Balanced Accuracy-ClustCent](https://user-images.githubusercontent.com/106329824/194072841-3bd2a3ed-8682-4e58-9fdc-4883d7a2f0da.png)

  * The precision is 0.99, so the correct positive predictions are 99% accurate compared to the total positive predictions.
  ![Report-ClustCentPre](https://user-images.githubusercontent.com/106329824/194072891-3e5fc1cf-386e-4883-aed5-0a11e28f41b2.png)

  * The recall is 0.4, so the correct positive predictions are 40% accurate compared to the total actual positive predictions.
  ![Report-ClustCentRec](https://user-images.githubusercontent.com/106329824/194072906-96f3dc3f-8996-4b18-867e-0af1b541e16d.png)

* SMOTEENN
	* The balanced accuracy score is 0.64, so the predictions are over 60% accurate.
  ![Balanced Accuracy-SMOTEENN](https://user-images.githubusercontent.com/106329824/194073016-d996bf47-d856-4a16-8908-e23c3cc722c6.png)

  * The precision is 0.99, so the correct positive predictions are 99% accurate compared to the total positive predictions.
  ![Report-SMOTEENNPre](https://user-images.githubusercontent.com/106329824/194072974-a69975a5-2c71-402b-910f-248bcaad300d.png)

  * The recall is 0.58, so the correct positive predictions are 58% accurate compared to the total actual positive predictions.
  ![Report-SMOTEENNRec](https://user-images.githubusercontent.com/106329824/194072992-e4785f7d-e384-4776-9ea4-983423c49192.png)

* BalancedRandomForestClassifier
	* The balanced accuracy score is 0.79, so the predictions are over 75% accurate.
  ![Balanced Accuracy-BRFC](https://user-images.githubusercontent.com/106329824/194073072-0ab3acb9-c85d-4a0b-bc7f-b3b2c25c6a30.png)

  * The precision is 0.99, so the correct positive predictions are 99% accurate compared to the total positive predictions.
  ![Report-BRFCPre](https://user-images.githubusercontent.com/106329824/194073109-6ed204e0-87f2-41f5-9792-31236ce3a086.png)

  * The recall is 0.87, so the correct positive predictions are 87% accurate compared to the total actual positive predictions.
  ![Report-BRFCRec](https://user-images.githubusercontent.com/106329824/194073097-64da5879-174c-4300-bd9a-54f27c6cd22d.png)

* EasyEnsembleClassifier
	* The balanced accuracy score is 0.93, so the predictions are over 90% accurate.
  ![Balanced Accuracy-EEC](https://user-images.githubusercontent.com/106329824/194073154-96876df7-cd27-4125-a578-856053eaeea9.png)

  * The precision is 0.99, so the correct positive predictions are 99% accurate compared to the total positive predictions.
  ![Report-EECPre](https://user-images.githubusercontent.com/106329824/194073208-ea163dd3-4b87-4be6-8b22-8863be2e11c1.png)

  * The recall is 0.94, so the correct positive predictions are 94% accurate compared to the total actual positive predictions.
  ![Report-EECRec](https://user-images.githubusercontent.com/106329824/194073219-ff938b90-deb5-4214-b5e2-b3e670c5ec8d.png)


## Summary
* As we can see, the easy ensemble classifier was the most accurate in predictions. Scoring 0.93 on balanced accuracy, this machine learning model will be the most useful when determining credit card risk. The second closest is balanced random forest classifier which comes in at 0.79. Then they continue to decrease, from random oversampler, 0.66, to SMOTE and SMOTEENN tying at 0.64, lastly to cluster centroids which scored a small 0.54
* I would recommend the model ‘easy ensemble classifier,’ due to its accuracy. Comparing to the rest of the models, this is the most reliable. 
