# project-bikesharing
This is a very simple Deep Learning model which is used to predict daily bike rental rideship.

# The dataset
Bike-sharing rental process is highly correlated to the environmental and seasonal settings. For instance, weather conditions,
precipitation, day of week, season, hour of the day, etc. can affect the rental behaviors. The core data set is related to  
the two-year historical log corresponding to years 2011 and 2012 from Capital Bikeshare system, Washington D.C., USA which is 
publicly available in http://capitalbikeshare.com/system-data. We aggregated the data on two hourly and daily basis and then 
extracted and added the corresponding weather and seasonal information. Weather information are extracted from http://www.freemeteo.com. 

### Checking out the data
<img width="375" alt="datast" src="https://user-images.githubusercontent.com/75294484/104161719-2a0c6a80-53a8-11eb-8f53-8150b303b844.png">

# The Neural Network
This network is built without any framework (pytorch, keras, tensorflow,...). In other words, this is a completely-from-scratch network.

### Training and Validation loss after the network is trained
<img width="372" alt="loss" src="https://user-images.githubusercontent.com/75294484/104162075-cdf61600-53a8-11eb-8002-96c6965ad11f.png">

# The predictions
<img width="503" alt="predict" src="https://user-images.githubusercontent.com/75294484/104162188-fc73f100-53a8-11eb-8829-9628eb3b700c.png">
