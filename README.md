Experts Map
==============
The Experts Map is a force directed graph that allows a web user to explore intersections of people across disciplines and research expertise. An example can be seen at https://vivo.colorado.edu/expertsmap

The Experts Map uses [D3.js](https://d3js.org) to render and searches an [Elasticsearch](https://github.com/elastic/elasticsearch) index. This Experts Map is derived from the [Find an Expert](http://findanexpert.unimelb.edu.au) Capability Map, an example of which can be seen at http://search.findanexpert.unimelb.edu.au/s/resources/unimelb-researchers/index.html#climate%7C20%7C1

The Elasticsearch index is populated by [VIVO-ISF](https://wiki.duraspace.org/display/VIVO/VIVO-ISF+Ontology) data using code derived from the [Deep Carbon Observatory](https://deepcarbon.net) faceted search VIVO integration found at https://github.com/tetherless-world/dco-elasticsearch

The original Capability Map was designed and developed by Matěj Korvas, Martin Kwok, Melissa Makin, and Simon Porter from University of Melbourne. This implementation is designed to work with the [Funnelback](https://www.funnelback.com) search engine over University of Melbourne VIVO data. To render the map, an interface has been built using D3.js over JSON data structures.
