# Proof of concept Virtual Scavenger Hunt.

Very rough proof of concept of virtual scavenger hunt using Google Maps.
Points are currently hard coded in the json variable, ideally these would be retrieved via AJAX.

You should just be able to open the file in a browser and things should work, however Chrome does not allow geoloation from file so if using this option in chrome your current location will be set to;

currentLocation.lat = 49.899488;
currentLocation.lng = -97.125425;

API_KEY will need to be set to a proper API_KEY value.