# Hohmann-Transfer-LEO-to-GEO-

Purpose: This module was made to calculate the the fuel consumption and delta v values of a spacecraft transferring orbits from LEO to GEO. Moreover, I took the parameters of the SpaceX Starship to calculate the fuel consupmtion needed for the most efficient maneuver possible to save on cost. Due to the large size of Starship and its vast transport capabilities this orbital transfer maneuver could be applicable to release satallites in various orbits within one mission.

Fliles:
1. Results file shows trajectory and values calculated. 
2. The code is in the Hohmann_transfer_LEO_to_GEO.ipynb file. Download file to manually enter parameters. Alternatively, you can use the python file.
3. Hohmann Notes.pdf includes some of the math and notes I took.

In the Hohmann_transfer_LEO_to_GEO.ipynb file:
This module is setup in the following way for each code box:
- 1. Hohmann transfer with statc mass
- 2. Non-static mass, with required input
- 3. Starship orbit transfer (no plot)
- 4. Starship orbit transfer (with plot)
- 5.  Starship orbit transfer (with plot of full ellipse)

Note: this project was built in Google Colab. If using local machine ensure the proper libraries are downloaded.
