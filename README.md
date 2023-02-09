# Mobile Price Range Prediction
Creating a ML model to predict the mobile price range
Mobile-Price-Range-Prediction In the competitive mobile phone market companies want to understand sales data of mobile phones and factors which drive the prices. The objective is to find out some relation between features of a mobile phone(eg:- RAM, Internal Memory, etc) and its selling price. In this problem, we do not have to predict the actual price but a price range indicating how high the price is.

Data Description -

Battery power - Total energy a battery can store in one time measured in mAh

Blue - Has bluetooth or not

Clock speed - speed at which microprocessor executes instructions

Dual sim - Has dual sim support or not

Fc - Front Camera mega pixels

Four g - Has 4G or not

Int memory - Internal Memory in Gigabytes

M dep - Mobile Depth in cm

Mobile_wt - Weight of mobile phone

N cores - Number of cores of processor

Pc - Primary Camera mega pixels

Px heig Px height - Pixel Resolution Height

Px width - Pixel Resolution Width

Ram - Random Access Memory in Mega Bytes

Sc h - Screen Height of mobile in cm

Sc w - Screen Width of mobile in cm

Talk time - longest time that a single battery charge will last

Three g - Has 3G or not

Touch screen - Has touch screen or not

Wifi - Has wifi or not

Price range - This is the target variable with value of 0(low cost), 1 (medium cost), 2(high cost) and 3(very high cost).

EDA:-

Prediction based on Mobile price.

Prediction based on Bluetooth connectivity .

Prediction based on Battery with price.

Prediction based on the RAM.

Prediction based on the weight.

Prediction based on the Battery power, pixels played etc.

MACHINE LEARNING MODEL:-

Logistic Regression.

Random Forest.

Decision Tree.

Support Vector Machine

# Random Forest Classification
 
Random forest classifier creates a set of decision trees from randomly selected subset of training set. It then aggregates the votes from different decision trees to decide the final class of the test object.Ensembled algorithms are those which combines more than one algorithms of same or different kind for classifying objects. For example, running prediction over Naive Bayes, SVM and Decision Tree and then taking vote for final consideration of class for test object.Basic parameters to Random Forest Classifier can be total number of trees to be generated and decision tree related parameters like minimum split, split criteria etc.

![image](https://user-images.githubusercontent.com/109582656/197851487-cac8d12b-da5b-451d-a389-193926233ecb.png)

# SVM Classifier

Support Vector Machine, or SVM, is a prominent Supervised Learning technique that is used for both classification and regression issues. However, it is mostly utilised in Machine Learning for Classification purposes.

The SVM algorithm’s purpose is to find the optimum line or decision boundary for categorising n-dimensional space so that we may simply place fresh data points in the proper category in the future. A hyperplane is the optimal choice boundary.
![image](https://user-images.githubusercontent.com/109582656/197851848-fbdef39a-414d-4601-8a59-6cdc28714130.png)

