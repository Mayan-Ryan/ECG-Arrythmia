# ECG-Arrythmia
Arrythmia Classification using MIT-PhysioNet

According to World Health Organization (WHO), cardiovascular diseases are responsible for approximately 31% of all deaths, out of which 82% are in low or middle-income countries, due to lack of high-quality electrocardiograms (ECGs) and shortage in medical experts to read and interpret the signal. Traditional cardiovascular (CVD) risk assessment includes algorithms such as the Framingham Risk Score (FRS), Systematic Coronary Risk Evaluation (SCORE) and Prospective Cardiovascular Munster (PROCAM). But ECGs have a vast collection of patient data stored in them. Due to this, a surge in many deep-learning and neural intelligence systems for medical diagnosis has occurred, especially for the prediction of arrythmias and coronary heart disease using Machine Learning Base Heart Disease Diagnosis (MLBHDD) models. Predictions are made based on risk factors such as:
	Age
  
  Blood pressure
  
  Sex
  
  Smoking habits
  
  Chest pain type (four values)
  
  Resting blood pressure
  
  Serum cholesterol in mg/dl
  
  Fasting blood sugar [120 mg/dl]
  
  Resting electrocardiographic results (values 0, 1 and 2)
  
  Maximum heart rate achieved
  
  Angina induced by Exercise
  
  Peak Old = ST depression tempted by workout comparative to rest
  
  Slant of the peak exercise ST segment
  
  Numeral of major vessels (0–3) colored by fluoroscopy.
  
  Thal: 3 = normal; 6 = fixed defect; 7 = reversible defect
  
The intelligence systems that are currently being deployed largely make use of the following machine learning algorithms:

o	Logistic Regression
Logistic Regression is a multivariate classifier that predicts based on the relationship between the dichotomous characteristics of a set of dependent and independent variables. It is used mostly for binary classification and is used to assign discrete values to classes. 
 
 ![image](https://user-images.githubusercontent.com/67265786/191623160-f44ae011-b40d-471e-b547-4d414027c5df.png)


y = β0 + β1x (in case of univariate Logistic regression)

y = β0 + β1x1 + β2x2 … +βnxn (in case of multivariate logistic regression)


o	Support Vector Machines (SVMs)
SVM is a technique of supervised machine learning used for classification and regression. SVM allows achieving results without solving any intermediary problems. This is achieved by separating the dataset into classes with a surface that maximizes the margin between them. It is an implementation of the Structural Risk Minimization Principle.

o	Artificial Neural Networks (ANNs)
Artificial Neural Networks are modelled on the brain and its functioning. ANNs consist of a network of artificial neurons. The connections are called parameters and learned knowledge from a data set is then represented by these model parameters. Also, an ANN model does make assumption about the dataset prior to training. The most popular ANN model is the Multi-Layer Perceptron(MLP).
