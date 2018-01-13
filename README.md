# Proj1_PumpkinSquirrelJuice

Project Title: Visual UI for MARTA

Team Members:
Daryl Bilderback
Nic Branker
Limbert Bontigao
Gene Cannella
Thomas Gentle
Tyler Maran

Project Description: 
STAGE1:
Our Team wants to have a Graphical Map of the MARTA Rail system, showing all Trains, incoming Trains, Traine Delay notifications, etc.

Sketch of Final Project:

APIs to be used: MARTA API, Google Maps API

Rough Breakdown of Tasks:
1) Create UI

2) Figure out User's Location by interfacing Google location to assign closest MARTA Station

3) Call the MARTA API to populate the a Database (ex. Firebase)

4) UI will call the Firebase Database to display the Graphical interface


1/13/18 Update
Ideas and items to consider:
- Using SVG JS to animate the map
  - Create HTML Canvas and use JS for train animation
  - Make items on this map clickable (for station select)
- Make sure trains are never double counted
  - Pull train ID's to see if any station lists the same station as a prior one


