# Flight-Fare-Prediction

Welcome to the Flight Fare Prediction project repository! In this project, we aim to predict the fare of airline tickets based on various factors such as flight duration, days left for departure, arrival time, departure time, and more. We leverage the power of Artificial Intelligence (AI) and Machine Learning (ML) techniques to build predictive models that can effectively estimate the price of airline tickets.

### Project Overview
Airline ticket pricing has become increasingly complex due to factors such as demand fluctuations, route popularity, and seasonal trends. To address this complexity, we utilize advanced ML algorithms to analyze historical data and predict future ticket prices accurately.

### Architecture
![Airplane](https://github.com/prajaktasonawane11/Flight-Fare-Prediction/blob/main/ProjectArchitecture.png)

### Dataset Description
The dataset used in this project contains information about airline tickets, including:
<ul>
  <li>Airline: The name of the airline company.</li>
  <li>Date_of_Journey: The date of the journey.</li>
  <li>Source: The origin airport.</li>
  <li>Destination: The destination airport.</li>
  <li>Route: The flight route.</li>
  <li>Dep_Time: The departure time.</li>
  <li>Arrival_Time: The arrival time.</li>
  <li>Duration: The duration of the flight.</li>
  <li>Total_Stops: The total number of stops during the journey.</li>
  <li>Additional_Info: Additional information about the flight.</li>
  <li>Price: The price of the airline ticket.</li>
</ul>

### Techniques Used
We employ various ML techniques and data preprocessing methods to train our models, including:

<ul>
  <li> Data cleaning and preprocessing to handle missing values and categorical variables.</li>
  <li> Feature engineering to extract useful information from date and time columns.</li>
  <li> Model selection and evaluation using algorithms such as Linear Regression, Random Forest, and XGBoost.</li>
  <li> Hyperparameter tuning to optimize the performance of our models.</li>
</ul>

### Steps Followed

<ul>
  <li>Data Preprocessing: We clean the dataset and handle missing values to prepare it for model training.</li>
  <li>Feature Engineering: We extract relevant features from the dataset, such as day of the week and month of the journey, to enhance model performance.</li>
  <li>Model Training: We train multiple ML models using the preprocessed data and evaluate their performance.</li>
  <li>Model Evaluation: We evaluate the trained models using metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) to assess their predictive accuracy.</li>
  <li>Deployment: We deploy the best-performing model to predict flight fares in real-time.</li>
</ul>

### Models Trained
We train several models to predict flight fares, including:
<ul>
  <li>Linear Regression</li>
  <li>Random Forest Regressor</li>
  <li>XGBoost Regressor</li>
</ul>

### How to Use
To use the predictive model:
<ul>
  <li>Clone this repository to your local machine.</li>
  <li>Install the required dependencies listed in requirements.txt.</li>
  <li>Run the provided scripts to preprocess the data and train the model.</li>
  <li>Once the model is trained, you can use it to predict flight fares by providing relevant input data.</li>
</ul>

### Conclusion
Flight Fare Prediction is a challenging yet rewarding task that can greatly benefit travelers and airline companies alike. By leveraging AI and ML techniques, we can make accurate predictions about future ticket prices, allowing travelers to plan their trips more effectively and airlines to optimize their pricing strategies. Thank you for visiting our repository, and we hope you find our project informative and insightful!

## Happy flying! ✈️🚀
