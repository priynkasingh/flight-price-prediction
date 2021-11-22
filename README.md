## flight-price-prediction
Predict the airline fare for flights in India based on the dataset available on Kaggle {https://www.kaggle.com/nikhilmittal/flight-fare-prediction-mh} using different regression models namely Linear Regression, Random Forest Regressor and KNN Regressor. 

## Highlights

### Features
The features used in the predictive modelling of Price are -
1. Airline - The airline company           
2. Date_of_Journey - The date of journey   
3. Source - City of Departure            
4. Destination - City of Arrival       
5. Route - The route undertaken for travelling to the destination city             
6. Dep_Time - The depature time of flight          
7. Arrival_Time - The arrival time of flight      
8. Duration - The duration of the flight          
9. Total_Stops - Number of halts in the journey       
10. Additional_Info - Some additional information related to the flight

### Methodology of the Analysis
- The data was cleaned throughly, the columns were converted into correct formats, label encoding was performed and outliers were handled. 
- Exploratory Data Analysis was carried out using Plotly and Seaborn to visualise the relation betweent the independent and dependent variables.
- Feataure selection was done using Mutual Information criteria. 
- R2 and Root mean square error were considered for evaluation of the performance of the machine learning algorithmns used - Linear Regression, Random Forest Regressor and KNN Regressor.
- Random Forest Regressor showed the highest performance. Further, GridSearchCV was used to select the hyperparameters for Random Forest to improve the R2 score from 0.825 to 0.849. 
