# map
Using Google Map API with $_GET request to query a database and output the results on a map 

Working example can be found at canvass.derek-nolan.com
To test type in either 'briarfield' or 'castletroy' or 'limerick'

You will need to add your database details to dbinfo.php
You will also need to get an API key form Google Maps API and add it to the url of the script tag at the bottom of index.php

You can use the below query to populate data in database

INSERT INTO `markers` (`id`, `name`, `address`, `lat`, `lng`, `type`) VALUES ('5', 'Love.Fish', '2 Cedars Briarfield Castletroy Limerick', '52.6662335', '-8.5579111', '');
INSERT INTO `markers` (`id`, `name`, `address`, `lat`, `lng`, `type`) VALUES ('6', 'Young Henrys', '4 Cedars Briarfield Castletroy Limerick', '52.6663705', '-8.5581241', '');
INSERT INTO `markers` (`id`, `name`, `address`, `lat`, `lng`, `type`) VALUES ('7', 'Hunter Gatherer', '6 Cedars Briarfield Castletroy Limerick', '52.6664934', '-8.5583507', '');
