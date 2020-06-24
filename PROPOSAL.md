<center> <h1>Data Analysis on Renting Options in Sydney: Airbnb </h1> </center>

![alt text](https://miro.medium.com/max/1068/1*BsKbDTA9ZUVroeJ7asId4Q.png?style=centerme)


## Group C

**Agam Kachhal  (45762643)**
**Yash Masand   (45513295)**
**Sairam Kaleru (45732590)**
**Shubham Rana  (45812713)**

## Introduction
Airbnb is an online platform for organizing or offering services for accommodation focusing mainly on homestays and holiday experiences. The company is based in San Francisco, California, United States. Users can list their homes/properties on Airbnb as hosts and people can make online bookings by getting in contact with their respective hosts.
    
We are going to do analysis using various variables such as price ratings house rules etc.  which are primarily focused by consumers to use Airbnb and provide a report in an interactive visualization format focusing on all kinds of audiences including naive users as well. Moreover we will come up with a prediction model to predict the patterns or trends between the Airbnb data and Australian Census data.
    
## Project Goals
    
1) Price comparison of various accommodations across all the suburbs in Sydney to depict the price variations in each suburb using various plots provided by various packages in Python.
    
2) Amenities are the very first requirement that comes to a new tenant’s mind prior to selecting a suitable property for rent in a new country or city. We will develop a predictive model to find out the effect of amenities provided based on the price of the listings.
    
3) To find out whether the price is directly proportional to only ratings or if it depends on other variables as well. RFE (Recursive Feature Elimination) will be used to predict the prices and then the predicted and actual prices will be compared based on the number of features provided by the model.
    
4) Understanding if the income of a particular suburb has any relation with the listings of the respective suburb. To achieve this we will join Census data with the Airbnb data to find their correlations.
    
## Data Overview
    
Precisely two datasets are going to be used in this project which is summarized as below:

1) Airbnb Dataset: This dataset includes the entire data gathered & required by Airbnb for their customer bookings. For instance it contains the host details room descriptions prices ratings and many more.
    
**Format:** Comma Separated File (.csv)
    
**Dataset Source:** [Airbnb Data](http://insideairbnb.com/get-the-data.html) (For Sydney)
    
**Pre Work:** Data Cleaning is required to clean the unorganized data (A blend of Blank and Junk Values Special Characters Regular Expressions etc.)
   
2) Australian Census Data for individuals with average salaries/wages: This dataset includes census data for individuals with average salaries/wages. It stores data with multiple columns/variables according to their respective zip codes.
    
**Format:** Comma Separated File (.csv)
    
**Dataset Source:** [Census Data](https://data.gov.au/data/dataset/540e3eac-f2df-48d1-9bc0-fbe8dfec641f/resource/d2804aa6-4c32-453c-9d60-d957e9028952/download) 
    
**Pre Work:** Remove Blank spaces in the data as it holds only numerical data.
    
## Techniques
    
We expect to make use of Regression Techniques RFE k-means clustering algorithm etc. to accomplish what has been laid out in the aforementioned "Project Goals" section. Predictive modeling will be used to predict whether the price is affected by only amenities or other variables as well and if they have an impact on the price of the listings. Data Visualization techniques will also be used to understand the trends and patterns in the data.
    
## Project Plan
    
**Plan#1:** Project Base and Proposal - **Week 7**
    
Data Scraping from web sources has been completed and we have data in .csv files.
    
**Plan#2:** Data Cleaning – **Week 9**
    
Data Cleaning activity on both the datasets to proceed with data analysis later on.
    
**Plan#3:** Model Creation and Analysis – **Week 11**
    
Predictive model analysis and initial Visualization
