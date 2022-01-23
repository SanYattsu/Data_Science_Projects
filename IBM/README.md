# Capstone project **"Winning Space Race with Data Science"**

In the project, we use a variety of machine learning models to predict the successful landing of Falcon 9 rocket, the optimum method to predict if the first stage will land successfully was founded. SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each. As we know, much of the savings that helps to evaluate the cost comes from the first stage rocket reuse. That’s why the cost of a launch can also be determined based on its successful landing. The results of the work can be used if an alternate company wants to bid against SpaceX for a rocket launch.

## During the work we:
- Perform Web scraping and made a get request to the SpaceX API to collect Falcon 
9 data.
- Perform Exploratory Data Analysis (EDA), Feature Engineering and determine 
Training Labels.
- Build an Interactive Map with Folium and Dashboard with Plotly Dash.

## The main results:
- The best Hyperparameter for SVM, Classification Trees and Logistic Regression is 
found.
- The method that performs best in the first stage rocket successful landing 
prediction using test data is found. 

## Data
- We made a get request to the SpaceX API and performed web scraping to collect Falcon 9 historical launch records from a Wikipedia page.
- We perform data wrangling and downloaded the dataframe, found bad outcomes, and picked the classification variable that represents the outcome of each launch
