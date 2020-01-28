**Proof of concept only** 

# Leaflet.SLDStyler

Example:

    var SLDStyler = new L.SLDStyler(SLDXmlOrText);

    var geojsonLayer = L.geoJson(jsonObject, {
       style: SLDStyler.getStyleFunction()
    }).addTo(map);
