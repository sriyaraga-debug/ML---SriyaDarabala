Predicting Orbital Elements Machine Learning Project 
By: Sriya Darabala

Goals:
The goal of this project is to take live position and velocity component data from satellites 
to predict certain orbital metrics such as the Right Ascension of Ascending Node (RAAN), 
argument of perigee (AoP), and inclination, which would then be used to make predictions about 
an orbital trajectory.

Dataset:
The dataset was obtained from the NASA JPL website and consists of Ephemeris Data of the ISS. 
These files are stored in the Data folder, which contains the vector data and orbital element 
data, both of which need to be downloaded. 

Model/Method used: LSTM neural network + model tuning and variations

Instructions to run the code:
First, download the data files from the data folder and upload them to your Google Drive. Run the
"ML_Project_code" file. In the first cell, update the file import path to match where they are 
stored in your drive. Once the data is imported, the rest of the code can be run to obtain the results.

Conclusions: 
Of all the models run, the 3rd model (1 LSTM layer with 100 neurons, Dense Layer with 50, and Dense 
layer of 3 neurons) performed best in determining orbital elements. Inclination was predicted with the 
best accuracy, while AoP was not predicted well by this approach.
