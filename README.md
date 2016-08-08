=======
Nomster
=======

Nomster is a Yelp-style clone built using Ruby on Rails 4.0.  The front-end is built with Twitter Bootstrap 3.  Viewers can retrieve a list of places with corresponding descriptions, photos, maps, and comments.  Registered users can create their own places, make comments on any places, upload photos to their places, and edit or delete their places.  

Dependencies
============
Devise: user authentication

Carrierwave: image uploads for place photos

Kaminari: pagination for places list

Simple Form: faster form generation

Geocoder: converting addresses to latitude and longitude for pinning on a map, used to connect to Bing street service API

Figaro: secure API keys in ENV variable

Fog: used to store images on Amazon S3
