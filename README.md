# AerofoilPressurePrediction
Using machine learning techniques, I predict the pressure distribution over a NACA0012 aerfoil for a range of angle of attacks and Reynold numbers.
The Literature Review pdf is a report of the methodology and motivation behind the project.
In summary, I use a decision tree and random forest algorithm, trained using a publically available aerofoil simulation tool, to predict the pressure distribution around a NACA0012 Aerofoil. An RMSE of 0.027 is achieved for compressible, turbulent flow that captures boundary layer seperation and non-linearities within the data.
