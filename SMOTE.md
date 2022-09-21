ECG datasets are highly class imbalanced since normal heartbeats appear much more frequently than abnormal heartbeats, resulting in most methods having low sensitives and positive predictive values on minority class ectopic heartbeats. 

Unbalanced data problem can solved by using the over-sampling approach. This sampling technique is known as Synthetic Minority Over-sampling Technique(SMOTE). This technique can increase the amount of data in the minority in the original data, by creating mock data to expand the area of decision-making to the minority class. To solve data imbalance, the existing data is resampled to determine accuracy of the sample dataset and provide a picture at random with replacement using data from a subset of the available data. Then SMOTE is implemented to balance the data of each class minority. The value of the over-sampling rate was adjusted by the amount of data for each level, using a healthy level as a reference, established using SMOTE. Here the resampling process produces a better data distribution, while SMOTE duplicates the data, so it becomes balanced. SMOTE also provides attributes whose values are not within the range of the attribute values. 

![image](https://user-images.githubusercontent.com/67265786/191623926-122406fe-bc92-465f-b15c-0d453c6a0903.png)

**SMOTE over MIT PhysioNet Database for an SVM Classifier **
