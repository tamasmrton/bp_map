# Budapest Public Transport Map

This mini-project represents the map of the public transport system in Budapest. \
The aim of this notebook is to visualize GTFS data specific to Budapest. The methods & functions used here are universal, and therefore, can be used on any other GTFS data.

General Transit Feed Specification (GTFS) is a widely used data specification framework that enables a common data format to be used by agencies to publish their transit data to be consumed by softwares. Budapest Közlekedési Központ (BKK), the transport agency of Budapest, publishes the transit data using the GTFS specification. GTFS has a rich metadata, therefore, it is easy to use and to implement for projects like this one.

In this project I enrich the GTFS data with geojson specifications of the different jurisdicial districts in Budapest. I will use the districts to create on the map. One could use this filter to know which vehicles enter/leave a specific district.

Furthermore, I will briefly introduce the libraries I used to create a map of routes in Budapest. Then, I will briefly discuss the functions to download, extract & enrich GTFS data. Then, I will show the transformations I added to the data. Lastly, the results section showcases the map produced.
