# Testmap
<!DOCTYPE html>
<html>
<head>
    
    <meta http-equiv="content-type" content="text/html; charset=UTF-8" />
    
        <script>
            L_NO_TOUCH = false;
            L_DISABLE_3D = false;
        </script>
    
    <style>html, body {width: 100%;height: 100%;margin: 0;padding: 0;}</style>
    <style>#map {position:absolute;top:0;bottom:0;right:0;left:0;}</style>
    <script src="https://cdn.jsdelivr.net/npm/leaflet@1.9.3/dist/leaflet.js"></script>
    <script src="https://code.jquery.com/jquery-3.7.1.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/js/bootstrap.bundle.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/leaflet@1.9.3/dist/leaflet.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css"/>
    <link rel="stylesheet" href="https://netdna.bootstrapcdn.com/bootstrap/3.0.0/css/bootstrap-glyphicons.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.2.0/css/all.min.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/Leaflet.awesome-markers/2.0.2/leaflet.awesome-markers.css"/>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/python-visualization/folium/folium/templates/leaflet.awesome.rotate.min.css"/>
    
            <meta name="viewport" content="width=device-width,
                initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
            <style>
                #map_443d6da251dd8c9e12218fa12fc69cbc {
                    position: relative;
                    width: 100.0%;
                    height: 100.0%;
                    left: 0.0%;
                    top: 0.0%;
                }
                .leaflet-container { font-size: 1rem; }
            </style>
        
</head>
<body>
    
    
            <div class="folium-map" id="map_443d6da251dd8c9e12218fa12fc69cbc" ></div>
        
</body>
<script>
    
    
            var map_443d6da251dd8c9e12218fa12fc69cbc = L.map(
                "map_443d6da251dd8c9e12218fa12fc69cbc",
                {
                    center: [39.9526, -75.1652],
                    crs: L.CRS.EPSG3857,
                    ...{
  "zoom": 13,
  "zoomControl": true,
  "preferCanvas": false,
}

                }
            );

            

        
    
            var tile_layer_2e1171481a277e0de3c3052111be724c = L.tileLayer(
                "https://tile.openstreetmap.org/{z}/{x}/{y}.png",
                {
  "minZoom": 0,
  "maxZoom": 19,
  "maxNativeZoom": 19,
  "noWrap": false,
  "attribution": "\u0026copy; \u003ca href=\"https://www.openstreetmap.org/copyright\"\u003eOpenStreetMap\u003c/a\u003e contributors",
  "subdomains": "abc",
  "detectRetina": false,
  "tms": false,
  "opacity": 1,
}

            );
        
    
            tile_layer_2e1171481a277e0de3c3052111be724c.addTo(map_443d6da251dd8c9e12218fa12fc69cbc);
        
    
            var circle_marker_368f33d07aa01f504282cbf08176877d = L.circleMarker(
                [39.889938, -75.176788],
                {"bubblingMouseEvents": true, "color": "indigo", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "indigo", "fillOpacity": 0.6, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 6.32, "stroke": true, "weight": 3}
            ).addTo(map_443d6da251dd8c9e12218fa12fc69cbc);
        
    
            circle_marker_368f33d07aa01f504282cbf08176877d.bindTooltip(
                `<div>
                     Station ID: 3183<br>Trips: 316
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            var circle_marker_973459e8775d7903d2f5fb6473170f73 = L.circleMarker(
                [39.917999, -75.179604],
                {"bubblingMouseEvents": true, "color": "indigo", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "indigo", "fillOpacity": 0.6, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 21.04, "stroke": true, "weight": 3}
            ).addTo(map_443d6da251dd8c9e12218fa12fc69cbc);
        
    
            circle_marker_973459e8775d7903d2f5fb6473170f73.bindTooltip(
                `<div>
                     Station ID: 3267<br>Trips: 1052
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            var circle_marker_564990ad68f01a67319e2b960e5842be = L.circleMarker(
                [39.917171, -75.170959],
                {"bubblingMouseEvents": true, "color": "indigo", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "indigo", "fillOpacity": 0.6, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 17.86, "stroke": true, "weight": 3}
            ).addTo(map_443d6da251dd8c9e12218fa12fc69cbc);
        
    
            circle_marker_564990ad68f01a67319e2b960e5842be.bindTooltip(
                `<div>
                     Station ID: 3237<br>Trips: 893
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            var circle_marker_53f26e5e4667c24d6c23133d4caab647 = L.circleMarker(
                [39.92083, -75.170326],
                {"bubblingMouseEvents": true, "color": "indigo", "dashArray": null, "dashOffset": null, "fill": true, "fillColor": "indigo", "fillOpacity": 0.6, "fillRule": "evenodd", "lineCap": "round", "lineJoin": "round", "opacity": 1.0, "radius": 21.5, "stroke": true, "weight": 3}
            ).addTo(map_443d6da251dd8c9e12218fa12fc69cbc);
        
    
            circle_marker_53f26e5e4667c24d6c23133d4caab647.bindTooltip(
                `<div>
                     Station ID: 3197<br>Trips: 1075
                 </div>`,
                {
  "sticky": true,
}
            );
        
    
            tile_layer_2e1171481a277e0de3c3052111be724c.addTo(map_443d6da251dd8c9e12218fa12fc69cbc);
        
    
            tile_layer_2e1171481a277e0de3c3052111be724c.addTo(map_443d6da251dd8c9e12218fa12fc69cbc);
        
</script>
</html>
