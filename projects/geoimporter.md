---
layout: project
type: project
image: img/geoimporter/geoimporter-square.png
title: "Geoimporter"
date: 2022
published: true
labels:
  - Python
  - API
summary: "GUI tool to easily interact with Geoserver API"
---

<img class="img-fluid" src="../img/geoimporter/geoimporter_screenshot.png">

The GUI is built with Tkinter in Python. The tool utilizes other python
packages (geoserver-rest, Geopandas, psycopg2) to easily interface with the
Geoserver REST API, and the PostGIS Postgres database. The tool is a solution
to uploading, and managing multiple data layers that are hosted by the
Geoserver. Due to Geoserver's data web interface, there is no fast way to
upload multple layers all at once, and also searching and deleting layers is a
tedious task. Lastly, I wanted to enable users to upload and delete shapefiles
in the Postgres database easily without having to use a database client. This
Geoimporter tool extends the Geoserver management capabilities by interface
with the REST API service.

Source: <a href="https://github.com/skimura1/geoimporter"><i class="large github icon "></i>skimura1/geoimporter</a>
