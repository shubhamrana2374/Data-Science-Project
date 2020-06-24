ITEC657 Group Project
===

**data-science-project-itec_pract_02-thu-2pm-_group-c**

*Group Members:* <br>
**Agam Kachhal  (45762643)** <br>
**Yash Masand   (45513295)** <br>
**Sairam Kaleru (45732590)** <br>
**Shubham Rana  (45812713)** <br>

## Project Title: Data Analysis on Renting Options in Sydney: Airbnb ##

We obtained our dataset from [Airbnb Data](http://insideairbnb.com/get-the-data.html) for Sydney. The csv file that we have used is named as ![#c5f015](https://placehold.it/15/c5f015/000000?text=+) `listings` and it contains _38080 rows and 106 columns_. 
This data is quite untidy and there are a number of columns which are not required as part of our analysis, so we have dropped those columns and are only working on 50 columns.
The other dataset that we have used is [Census Data](https://github.com/MQCOMP257/data-science-project-itec_pract_02-thu-2pm-_group-c/blob/master/Dataset/CensusData.csv). This csv file initially had 2473 rows and 34 columns. For our analysis, we dropped several columns and worked upon only 8 columns. After joining both these datasets we had a total of 58 columns in all.

## Challenges Faced ##

1. *git lfs not supported* - Git Large file storage is not supported for this repository and as our data file for airbnb data named ![#c5f015](https://placehold.it/15/c5f015/000000?text=+) `listings.csv` is over 100MB in size, so we could not push it to the git repo. To overcome this situation, we have marked and kept it as a hyperlink in this `readme.md` whose link can be found above in the project title with the name `Airbnb Data`. <br>

2. *Plotly Interactive graphs not rendered by Github* - We have created an interactive heatmap and a 3D plot using plotly library and pushed those changes in our repository. However, we encountered that these interactive plots are not rendered by Github due to which we cannot see our changes in the repository. To overcome this situation, we downloaded our project.ipynb file as HTML and pushed that in our repository. In the HTML file all the interactive plots are properly displayed.

## Below mentioned libraries have been used in our data analysis:

1. `numpy` <br>
2. `pandas` <br>
3. `seaborn` <br>
4. `matplotlib` <br>
5. `wordcloud` <br>
6. `nltk` <br>
7. `collections` <br>
8. `cufflinks` <br>
9. `plotly` <br>
10. `sklearn` <br>

## Source Code Referencing

1. *Wordcloud Implementation* - We used the following link for the purpose of implementing the wordcloud on our columns having data as text: <br>
[wordcloud](https://towardsdatascience.com/identify-top-topics-using-word-cloud-9c54bc84d911)

2. *Model Building* - We referred to our Weekly practical workshop classes to implement K-nearest-neighbour, Neural Network, Linear and Logistic regression models.

## Data Cleaning ## 

As part of our data cleaning activity, We have updated various variable types and have handled boolean type values for some columns. Mapping of string to numerical categorical values have been addressed. The column __`amenities`__  was a list displaying the number of amenities provided in each listing .We have splitted that list and printed out the total number of amenities for each listing as a numerical value. After splitting we have created a new column called __`amenities_count`__ that holds numerical values of data so that it's easier to plot them later on. <br>
No data cleaning was required for the other csv file [Census Data](https://github.com/MQCOMP257/data-science-project-itec_pract_02-thu-2pm-_group-c/blob/master/Dataset/CensusData.csv) as it had all the numerical data. For further detailed analysis about Data Cleaning, please refer to `project.ipynb` file.

- [x] Finished Data Cleaning

## Data Analysis and Visualization ##

We have implemented various plots for our data analysis including `KDE (Kernel Density estimate)`, `catplot`, `factorplot`, `interactive heatmap`, `barplot`, `stripplot`, `scatterplot`, `interactive 3D plot` to depict the relationship between various variables as to they are positively correlated or not and to understand the patterns and trends in data. <br>
Wordcloud has also been implemented on columns containing data type as string (`house_rules` and `transit`). For the further data analysis, please refer to the section `Data Analysis and Visualization` in `project.ipynb` file.

- [x] Finished Data Analysis


## Model Building and Prediction ##

### On individual dataset (airbnb) ###
### Predicting - Price Class ###

__`Price Class`__ - We divided price into three classes i.e. price of listings equal or less than 125 dollars is kept as 0 (low), price of listings between 125 and 200 dollars is classified as 1 (medium) and price of listings greater than 200 is classified 2 (high). <br>
We have implemented __`Logistic regression and K-nearest-neighbour`__ on the `airbnb dataset` and the __`price`__ class of the listings provided in the dataset. After the implementation, we got a model accuracy of __`70.77% for Logsitic Regression and an accuracy of 64.55% for the K-nearest-neighbour model`__. <br>
So, we concluded that the Logistic Regresison model outperforms the K-nearest-neighbour model in terms of accuracy in predicting price class on the airbnb dataset.

### On joined dataset (airbnb with census) ###
### Predicting - Price Class ###

We have implemented __`Logistic regression and K-nearest-neighbour`__ after joining `census dataset with the airbnb dataset` and we are predicting the __`price`__ class in this case using joined data. After the implementation, we got a model accuracy of __`65.03% for Logistic Regression and an accuracy of 66.28% for the K-nearest-neighbour model`__. <br>
So, we concluded that on joining the dataset, K-nearest-neighbour model outperforms the logistic regression model in terms of accuracy in predicting price class.

### On joined dataset (airbnb with census) ###
### Predicting - Price ###

We have implemented __`Linear Regression, Decision Tree Regressor and Neural Networks`__ after joining census dataset with the airbnb dataset and we are predicting just `price of the listings` in this case. After the implementation of all these models, we got the best accuracy on Decision Tree Regressor with a percentage of `55.75%`.

- [x] Finished Model Building and Prediction

# Project Conclusion #

After the implementation of all the above mentioned models, we can conclude that the performance of the models can be increased with feature engineering and by applying the techniques of Text Processing. <br>
The models might not be predicting that accurately, as most of the features in our dataset contain data in the form of text.Using a dataset having more numerical values can lead to a model predicting more efficiently.
