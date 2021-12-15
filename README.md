# Binary-Classification-of-Asteroids
 This analysis seeks to establish a predictive classification model for identifying “hazardous” asteroids using features such as its mass, velocity, and some orbital characterizations. The goal is to select a meaningful classification model with acceptable accuracy, recall, precision, and AUC score to provide insights to NASA and other federal agencies in charge and help identifying the hazardous asteroids.
## Data
The data about asteroids for this project has been collected from the NASA open API and available on [Kaggle](https://www.kaggle.com/shrutimehta/nasa-asteroids-classification). NEOWs (Near-Earth Object Web Service) is a RESTful web service for near earth Asteroid information. With NEOWs a user can search for Asteroids based on their closest approach date to Earth, lookup a specific Asteroid with its NASA JPL small body id, as well as browse the overall dataset. 
The dataset has 4,687 observations and 40 columns. The target is whether an asteroid is hazardous or not (True or False).
The feature columns include asteroid’s speed, some dimensions, and other orbital information.
