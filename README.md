# Titanic_Survival
**Completed by SOnakshi Chauhan.**
**Overview:** This project is using the Titanic Dataset to create a model that will 
-return a conditional survival probabily of a passenger 
-Help you comapre and contrast all the Classification models based on accuracy
-data vizualizations given a condition on a numerical variable from the dataset. 
**Problem Statement:** Build a model that will return a passengers survival chance given a passengers detail as input. 
**Data:** [Titanic Kaggle Challenge](https://www.kaggle.com/c/titanic)
**Deliverables:** Probability
**Ahoy! Let's Sail**
![image](https://user-images.githubusercontent.com/91408631/236147768-d38e20f2-9fb5-463a-895b-bdf245d7486c.png)
## Topics Covered
1. Statistical Modeling
2. Imputation of Missing values
3. Probability
4. Various Classification Techniques
## Tools Used
1. Scikit-learn
2. Google Colab
## Installation and Usage
Ensure that the following packages have been installed and imported.
```bash
pip install numpy
pip install pandas
pip install seaborn
```
#### Jupyter Notebook - to run ipython notebook (.ipynb) project file
Follow instruction on https://docs.anaconda.com/anaconda/install/ to install Anaconda with Jupyter. 
Alternatively:
VS Code can render Jupyter Notebooks
## Notebook Structure
The structure of this notebook is as follows:
 -Imports
 -Data Loading
 -Data Pre-processing
 -Data Analysis
 -Data Vizualization
 -Encoding
 -Supporting Target and Features
 -Spliting Data
 -Model Training
 -Testing and Prediction
# Data Pre-Processing
![image](https://user-images.githubusercontent.com/91408631/236141960-b32180b1-d28d-463b-a8ab-83cec87f6963.png)
->observing the data above we found it had missing columns and rows
->We dropped the 'Cabin' column as it had highest number pf missing values
->We manipulated the 'Age' and  'Embarked Column'
# Data Analysis
->Prediction has to be made depending on the survival number
->Here we analyze the number of survived people according to different classes
# Data Vizualizations
->Here we vizualize our data to have a better understanding of highest survivval rates are from which category.
![image](https://user-images.githubusercontent.com/91408631/236144604-f6067773-cf16-4add-ac21-f5967e4501c7.png)
![image](https://user-images.githubusercontent.com/91408631/236144674-69915a59-1ba7-4694-a226-0b3cf233e6e4.png)
![image](https://user-images.githubusercontent.com/91408631/236144747-27aa26fc-8a3a-4847-b940-d5573807c68b.png)
![image](https://user-images.githubusercontent.com/91408631/236144821-d6c76bce-2b55-4dea-bf5e-6c037cd6550e.png)
![image](https://user-images.githubusercontent.com/91408631/236144908-940a99f0-4e5d-4199-9429-7e5f29f0adbb.png)
#Categorial Encoding
->Here we encode all the values numerically so as to ensure similarity in data types
#Supporting Target and Features
->Here we divide data into dependent and independent variables mainly 'Y' having the dependent value and 'X' having independent values 
#Splitting our Dataset into Train and Test Set
->Using sklearn library we split our dataset into train and test
# Model Training
->First we scale our train and test set values
-> Here we train multiple classification models to choose which one is more accurate
-> We find RandomForest more accurate and move ahead with it.
#Prediction and accuracy
->This is the final step where we test and make predictions on our model
#Conclusion
->We built a Classifier using Random Forest technique to predict titanic survival rates
**Contact:** sonakshichauhan1402@gmail.com
## Project Continuity
This is project is complete
## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change. 
