# Binary-Classification-of-Asteroids
 This analysis seeks to establish a predictive classification model for identifying “hazardous” asteroids using features such as its mass, velocity, and some orbital characterizations. The goal is to select a meaningful classification model with acceptable accuracy, recall, precision, and AUC score to provide insights to NASA and other federal agencies in charge and help identifying the hazardous asteroids.
## Data
The data about asteroids for this project has been collected from the NASA open API and available on [Kaggle](https://www.kaggle.com/shrutimehta/nasa-asteroids-classification). NEOWs (Near-Earth Object Web Service) is a RESTful web service for near earth Asteroid information. With NEOWs a user can search for Asteroids based on their closest approach date to Earth, lookup a specific Asteroid with its NASA JPL small body id, as well as browse the overall dataset. 
The dataset has 4,687 observations and 40 columns. The target is whether an asteroid is hazardous or not (True or False).
The feature columns include asteroid’s speed, some dimensions, and other orbital information.
## Feature Columns Dictionary
Data Dictionary
Neo Reference ID - Near Earth Object (NEO) classification ID
Absolute Magnitude - The magnitude of an asteroid at zero phase angle and at unit heliocentric and geocentric distances.
Est Dia in KM(min)- This feature denotes the estimated diameter of the asteroid in the stated unit.
Relative Velocity km per sec- This feature denotes the relative velocity of the asteroid in kilometer per second.
Orbiting Body- This feature denotes the planet around which the asteroid is revolving.
Minimum Orbit Intersection- Minimum orbit intersection distance (MOID) is a measure used in astronomy to assess potential close approaches and collision risks between astronomical objects. It is defined as the distance between the closest points of the osculating orbits of two bodies.
Jupiter Tisserand Invariant - The value of Tisserand's criterion is also used to classify different types of comet's and asteroids into dynamical groups. Tisserand Invariant with respect to Jupiter.
Epoch Osculation -The instant of time at which the position and velocity vectors are specified is the epoch of osculation.
Eccentricity - One half of the major axis of the elliptical orbit; also the mean distance from the Sun.
Semi Major Axis - One half of the major axis of the elliptical orbit; also the mean distance from the Sun.
Inclination - Angle between the orbit plane and the ecliptic plane.
Asc Node Longitude - Angle in the ecliptic plane between the inertial-frame x-axis and the line through the ascending node.
Orbital Period - The time it takes an orbiting body to make one complete revolution around the Sun.
Perihelion Distance - An orbit’s closest point to the Sun.
Perihelion Arg - Angle in the orbit plane between the ascending node and the perihelion point.
Aphelion Dist - An orbit’s farthest point to the Sun.
Mean Anomaly - Truly anomaly is the angle in the orbit plane between the perihelion point and the position of the orbiting object
Hazardous - identification if asteroid is a Potentially Hazardous Asteroid (PHA)

