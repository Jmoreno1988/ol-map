# ol-map
#### A geographic information system (GIS) encapsulated in Web Component.

ol-map is a little geographic information system based in Web Components, Polymer and Openlayers.

More info: 
 - Web Components: http://webcomponents.org/
 - Polymer: https://www.polymer-project.org/1.0/
 - OpenLayers: http://openlayers.org/

### Example
 - Simple map: http://46.101.187.32/ol-map/index.html

### Installation
```sh
$ git clone https://github.com/Jmoreno1988/ol-map.git
```

### Usage
```sh
    <!DOCTYPE html>
	<html lang="en">
	<head>
	    <meta charset="utf-8" />
    	<title> Example ol-map </title>
    	
    	<!-- The webcomponent.js polyfills enable Web Components in (evergreen) browsers that lack native support. -->
    	<script src="ol-map/lib/webcomponentsjs/webcomponents-lite.min.js"> </script>
    	
    	<!-- Imports are a way to include and reuse ol-map -->
    	<link rel="import" href="ol-map/ol-map.html">
	</head>
	<body>

		<!-- ol-map web component -->
    	<ol-map latitude="-420000" longitude="4800000" zoom="4"></ol-map>
    	
	</body>
	</html>
```

### Contributing
Want to contribute? Great!... Fork, fork, fork!! ;)

### License
GNU GENERAL PUBLIC LICENSE v3

Copyright (C) 2016 JMoreno Games.