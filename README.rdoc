=======
Nomster
=======

Nomster is a Yelp-style clone built using Ruby on Rails 4.0.  The front-end is built with Twitter Bootstrap 3.  Viewers can retrieve a list of places with corresponding descriptions, photos, maps, and comments.  Registered users can create their own places, make comments on any places, upload photos to their places, and edit or delete their places.  

Dependencies
============

Nomster makes uses of the following gems:

<b>Devise</b>: user authentication

<b>Carrierwave</b>: image uploads for place photos

<b>Kaminari</b>: pagination for places list

<b>Simple Form</b>: faster form generation

<b>Geocoder</b>: converting addresses to latitude and longitude for pinning on a map, used to connect to Bing street service API

<b>Figaro</b>: secure API keys in ENV variable

<b>Fog</b>: used to store images on Amazon EC2
