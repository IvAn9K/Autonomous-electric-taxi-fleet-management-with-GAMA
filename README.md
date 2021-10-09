# Autonomous-electric-taxi-fleet-management-with-GAMA
A model used to simulate a fleet of autonomous electric taxis that will serve the clients that automatically appear in the city of Aranjuez. 
The model presented can be used as a basis for more complex real cases, since it offers a functional taxi service, where no taxi will run out of battery, 
but the objective function is balanced for my case (trying to minimize distance travelled, client's time wait and avoid having taxis that are moving freely without a client). 
The roads and node shapefiles has been done with QGIS, while the code itself has been done in GAMA 


To use this code, you need the GAMA tool and add there the model presented in this project. You will also need to add the includes folder since it has all the files
regarding nodes and roads, in order to generate the map of Aranjuez. Then, inside the model, you can modify everything freely or just used the proposed model. See both
GAMA and QGIS documentation in order to learn more about these two tools


GAMA Platform: https://gama-platform.github.io/

QGIS: https://qgis.org/es/site/about/index.html


Link to a video of the simulation: https://www.youtube.com/watch?v=38U0_PrvBUE
