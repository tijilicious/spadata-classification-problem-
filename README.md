<html>
  <h1>DETAILS</h1>

The data set SpaData.csv file contains a total of 6514 data points and a total of 7 features and binary label (0 or 1). 

The aim of the project is to determine if a room is occupied or not based on the features available. Not all features were used as there was no relation between the output and the feature such as ID.
Out of a total of 7 features availabe, 5 were used to train the model and predict an output where 1 means the room is occupied and 0 means that the room is not occupied.

Training data consists of 6000 data points and 514 points for testing.


<h1>DATA DESCRIPTION<h1>
  
  ID                  -	Room ID of the particular related GTO
  TimeStamp           - Date and time when the readings were recorded
  Temperature	        - Temperature of the room.
  RelativeHumidity    - Relative humidity of the room (Relative humidity tells us how much water vapor is in the air, compared to how much it could hold at that temperature.)
  Light	              - Light intencity
  OxygenLevels        - air oxyden levels 
  HumidityRatio	      - Humidity ratio is the ratio of weight of moisture to the weight of dry air in the air–vapor
  GTOccupancy         - This is the label which is binary where 1 is occupied and 0 is not occupied.
  
  
Tools used- Python3, SciKit-Learn, Random Forest Classifier and Hyperparameter Tuning using RandomizedSearchCV.
  
  

</html>
