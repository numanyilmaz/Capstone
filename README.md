# Predicting H1-B visa petitions

H-1B visas are taking long time to process which could be 1-2 years. According to paysa.com research, employees are staying at the big tech companies [less than 2 years.][2] After all, does it really make sense for big tech companies to go through visa process for an employee that may or may not be a fit for a position? To solve this problem, given the occupation name, job title, position type and salary, a model could give us the chance of acceptance before even file a petition. That would save so much time and money for big companies. 


### Dataset
Dataset for this project is from [Kaggle.][1] The raw data can be obtained at The Office of Foreign Labor Certification (OFLC) website as well. The dataset contains five year's worth of H-1B petition data(2011 - 2016) which is approximately 3 million records. 

### Initial notebook
nbviewer version of the notebook is [here.][3]

### Project Design

This project will consist of six categories. Each category is explained below. 

**Data collection:** Sometimes data is a collection of image, audio or text data. The dataset I will be using in this project is from Kaggle.

**Data Wrangling:** In this stage, dataset will be organized and cleaned to make it more usable for the next stages. 

**Data Exploring:** The data exploration stage is where some visualizations will be provided to understand the data. Some statistical methods will also be provided to gather information from data.

**Data Transforming:** Most of the times, data has to be scaled using a scaler method in order to prepare it for the model.In order to visualize dataset, dimensionality reduction techniques will be used to reduced to number of features. 

**Data Modeling:** As it is mentioned above, three machine learning algorithms will be used to train a model. These are Logistic Regression, Random Forest and Support Vector Machines. 

**Model Evaluation:** This is where the model will be scored.

### License
The contents of this repository are covered under the [MIT License.][4]


[1]: https://www.kaggle.com/nsharan/h-1b-visa
[2]: https://en.wikipedia.org/wiki/H-1B_visa#Duration_of_stay
[3]: https://github.com/numanyilmaz/Capstone/blob/master/Capstone.ipynb
[4]: https://github.com/numanyilmaz/Capstone/blob/master/LICENSE

