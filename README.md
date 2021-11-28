# ML-Project: Human Activity Recognition Using Data from Smartphone Sensors


## About the Topic
Human Activity Recognition is an active research area that has wide applications in healthcare and human survey systems. Activity detection is one of the most basic and common activities performed by humans on a daily basis. This ability is what makes us context aware and helps shape our decisions. Having information about what users are doing helps applications communicate intelligently. It can also help caretakers monitor the activity of patients and the elderly, and provide assistance when anomalous activities such as falling are detected.


## About the Project
Most smartphones have accelerometer and gyroscope sensors, data from which can be used for human activity recognition. For many people, mobile gadgets have become an inseparable part of their everyday lives. People have their phones with them at all times of the day, whether they are driving, exercising, walking, working, or taking a break.  Thus, human activity recognition from smartphone accelerometer and gyroscope data is easily accessible and widely applicable. Here we use machine learning methods to classify human activity using data collected from smartphone sensors

Our project aims to classify human activity as ‘Standing’, ‘Walking’, ‘Walking Upstairs’, ‘Walking Downstairs’, ‘Sitting’, or ‘Laying’ given smartphone accelerometer and gyroscope readings. We trained different machine learning models (Naïve Bayes, Decision Trees, Random Forest, Logistic Regression, SVM, K-Means, KNN, and ANN) using a dataset from UCI’s Machine Learning Repository for this purpose and compare their performances to select the best model.

## About our dataset
We have used a Kaggle dataset titled ‘Human Activity Recognition with Smartphones’ provided by UCI Machine Learning and licensed under a CC0. It contains data collected from 30 volunteers who performed activities of daily living while wearing a Samsung Galaxy S II mounted on their waist. Sensor readings from the device are present in the datasetThe activities performed fall into the following categories- Standing, Walking, Walking Upstairs, Walking Downstairs, Sitting, Laying. Each entry in the dataset contains:

* Triaxial acceleration (from accelerometer) and estimated body acceleration
* Triaxial Angular velocity (from gyroscope)
* A 561 feature vector with time and frequency domain variables
* The label

The raw data had been extracted, pre-processed, normalized, and divided into training and testing data using a 7:3 split. We further processed the data by performing dimensionality reduction.


## About the Repo
This repo contains the following:
* Models - Contains pickled models
* train.csv - Training dataset
* test.csv - Test dataset
* HumanActivityRecognition.ipynb - Jupyter notebook for the project containing the entire code and reults
* Report_Group 30.pdf - Report for the project in CVPR format
* README.md


## Dependencies
This project uses-
* [Python 3.10.0](https://www.python.org/downloads/)
* [Jupyter Notebook 5.7.6](https://jupyter.org/install)
* [Pandas 1.3.4](https://pandas.pydata.org/docs/getting_started/install.html)
* [Numpy 1.21](https://numpy.org/install/)
* [Matplotlib 1.5](https://matplotlib.org/downloads.html)
* [Seaborn 0.11.2](https://seaborn.pydata.org/installing.html)
* [Scikit-learn 1.0.1](https://scikit-learn.org/stable/install.html)
* [Joblib 1.1.0](https://pypi.org/project/joblib/)
* [Pickle](https://pypi.org/project/joblib/)


## Running the Models
You can load the model using the following code -
```
f = open("model_name", "rb")
load_model = pickle.load(f)
f.close() 
```


## Contributions 👽
Contributions are welcome. Please see the contribution guidelines, make sure you understand the code and have the dependencies set up.


## Need Help? 🤝
Feel free to make bug reports on our issues. You can reach out to either of us in case you need further assistance. 

*Contact us:*

* Aairah: aairah19003@iiitd.ac.in
* Dhairya: dhairya19035@iiitd.ac.in
* Harshit: harshit19044@iiitd.ac.in
* Kirthana: kirthana19053@iiitd.ac.in


*****

<p align="center">
Made with ❤️ by Group 30
</p>
