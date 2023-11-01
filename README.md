# Flight-fare-prediction
## 1).Dataset: https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction,   https://drive.google.com/file/d/1aiSqLZ2o7WUfydHeLHou035KeiaYeKw1/view?usp=sharing,            The data was collected with the goal of providing users with information that could help them make informed decisions about when and where to purchase flight tickets. By analyzing patterns in flight fares over time, users can identify the best times to book tickets and potentially save money.

## 2).About Project: The ML model used to predict the flight fare(in rupees).Dataset contains information about flight booking options from the website Easemytrip for flight travel between India's top 6 metro cities. There are 300261 datapoints and 11 features in the cleaned dataset.

          The various features of the cleaned dataset are explained below:
           1) Airline, Flight, Source, Departure Time, Stops, Arrival Time, Destination City, Class, Duration, Days Left,  Price. 
## 3).Algorithms and Accuracy of model: RandomForest regressor giving good performance on the Training and Test data.

### For Training data

![download (9)](https://github.com/Gaurav1917/Flight-fare-prediction/assets/146158309/394f2ed4-ba86-4145-9c4b-eb0972a6858e)


### For Test data

![download (10)](https://github.com/Gaurav1917/Flight-fare-prediction/assets/146158309/ff6810e0-9069-4a9b-bbe1-15d620fa85e1)



## 4)The aim of our study is to answer the below research questions:   

 #### a) Does price vary with Airlines?
 #### b) Does ticket price change based on the departure time and arrival time?
 #### c) How the price changes with change in Source and Destination?

### a) Does Price vary with Airlines?

![download (1)](https://github.com/Gaurav1917/Flight-fare-prediction/assets/146158309/ebb94e44-9155-4776-905d-c41c532ab28a)

Yes! Price vary with Airlines, Variation in price is given by:

       AirIndia=Vistara > StarAir > GO FIRST > SpiceJet=Indigo > AirAsia > AllianceAir > AkasaAir

       #AirIndia and Vistara has maximum fare.
       #AkasaAir has minimum fare.

### b) Does ticket price change based on the departure time and arrival time?

![download (6)](https://github.com/Gaurav1917/Flight-fare-prediction/assets/146158309/fa189db3-e2a0-4da4-8805-388d7878c66e)

![download (7)](https://github.com/Gaurav1917/Flight-fare-prediction/assets/146158309/a14b4775-3ed9-4a4c-93da-b3f442dbc482)

![download (8)](https://github.com/Gaurav1917/Flight-fare-prediction/assets/146158309/ec1c8d9d-56da-4391-b320-6592ffba3e07)

Yes! ticket price change based on the departure and arrival time:

        #Departure Time = Prices are maximum when Departure time is After 6 PM and minimum when Departure time is Before 6 AM.
        #Arrival Time = Prices are maximum when Departure time is 12 PM - 6 PM and minimum when Arrival time is 6 AM - 12 PM.

        If Departure Time is Before 6 AM and Arrival Time is 6 AM - 12 PM than you will have to pay minimum fare.

### c) How the price changes with change in Source and Destination?
![download (11)](https://github.com/Gaurav1917/Flight-fare-prediction/assets/146158309/f39fa275-a406-4b54-8f7c-6d314fe44526)

![download (3)](https://github.com/Gaurav1917/Flight-fare-prediction/assets/146158309/bf9c676b-2961-466d-ae1a-459e8564a6ca)

The variation in price with change in Source and Destination is given by:

       #)Kolkata to Mumbai - The price is maximum for this Route.
       #)Hyderabad to Ahmedabad - The price is minumum for this route
       
       It is also depends upon the path you want to take-
       #)non-stop = if you are taking non stop and your Destination is Delhi than the fare will be maximum and minimum when your destination is Ahmedabad.
                    Destination variation = (Ahemadabad < Hyderabad < Bangalore < Chennai < Mumbai< Kolkata < Delhi).
       #)1-stop = if you are taking 1-stop and your Destination is Mumbai than fare will be maximum and minimum when your destination is Ahmedabad.
                   Destination variation = (Ahemadabad < Delhi < Hyderabad < Bangalore < Chennai < Kolkata < Mumbai).
       #)2+-stop = if you are taking 2+-stop and your Destination is Chennai than fare will be maximum and minimum when your destination is Delhi.  
                   Destination variation = (Delhi < Mumbai < Hyderabad < Bangalore < Kolkata < Ahmedabad < Chennai)

        If you are taking non-stop than you will have to pay lowest price.  

### 5). Output.

#### Sample 1

![Screenshot (25)](https://github.com/Gaurav1917/Flight-fare-prediction/assets/146158309/23f31564-3c92-4836-9318-fe2635fd3f1a)



                   
       




  
