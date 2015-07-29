# FEWD50-final

Overview:

A repository for the final project of the Front End Web Development course I recently completed with General Assembly.

The goal of the project was to build a simple search application for my current employer, Learning Ally.  The search app should allow users to enter their location and see a result of nearby 'Specialists' (doctors).

What I used and why:

Bootstrap - for quick and easy mobile friendly views
Underscore JS - for a template to display the search results
Google Maps API - to geocode the users input, build map boundaries and display locations to user

Functionally Overview:

-The app takes a users location and turns it into a lat. and long. coordinate using Google Maps geocoding services.  
-This location is then given to Google Maps this time to create a map with this location at the center.  
-Once the map has then been created, the maps boundaries are used then compared to the data in our JSON file and returns only locations that are within those boundaries.
-Using Google Maps again, those returned locations are then populated visually on the map.

Enhancements:

-If a user moves the maps boundaries, the map should then take the new boundaries and return new locations discovered within those boundaries.
-Include an advanced search which would allow users to set location parameters: show results within 25, 50 or 100 miles
