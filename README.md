# trail-viz

**Work in progress**

A web frontend which visualizes live and offline geo-tracking data of current/previous bike+hiking tours using the OpenLayers library and map data provided by OpenStreetMaps and MapTiler.

Live data is gathered from compatible devices (OsmAnd Android app) on a server backend which then stores session data and publishes it via websocket connections to web clients, enabling live geo-tracking.

The idea of this project is to be able to share data of bike/hiking tours with family and friends (or anyone else), while also creating a database of past recordings that can be compared against each other.
