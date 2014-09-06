Geocoding resources for Bulgaria
==================

This is a collection of resources that should help anyone working with geocoding or mapping data in Bulgaria.

municipalities.csv
------------------
A list with all municipalities
- EKATTE - Bulgarian region coding system
- code - classification by the Statistics office
- name - in Bulgarian

settlements.csv
------------------
List with all cities, towns and villages in Bulgaria with geo coordinates. Currently 338 locations are missing coordinates
- EKATTE - Bulgarian region coding system
- code - classification by the Statistics office
- village - 0=city,town 1=village
- name - in Bulgarian
- geo - coordinages extracted from openstreetmap. Those missing are marked as "n/a"


municipalities.geojson
------------------
Borders of each municipality together with metadata
- name - in Bulgarian
- code - classification by the Statistics office
- oblast - name of province in Bulgarian
- nameEn - name in English
- oblastEn - name in English
- nuts3 - international region coding system

rpu_sofia.geojson
------------------
Borders of the regions of each police station in the capital Sofia
- name - name of the police station in Bulgarian
- description - explains the region with bordering streets and neighborhoods plus contact data. In Bulgarian
- url - website of the station
- id - unique id in ascii
- address - address of the station itself
- telephone - contacts
- populationEst - estimated population of the covered area
