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
Borders of the regions of each police station in the capital Sofia. Multipolygons mark only populated places for each reagion. Simple lines encircle the whole territory.
- name - name of the police station in Bulgarian
- description - explains the region with bordering streets and neighborhoods plus contact data. In Bulgarian
- url - website of the station
- id - unique id in ascii
- address - address of the station itself
- telephone - contacts
- populationEst - estimated population of the covered area

res_plants.tsv
------------------
Locations of all RES power plants connected to the grid until Dec 2013. In Bulgarian.
- code - identification by the Ministry of economy and energy
- type - type of power plant
- firma - company owning the plant
- bulstat - company identification
- fobshtina - municipality where the owner is registered
- fgrad - city/village where the owner is registered
- vei - name of the RES plant
- vobshtina - municipality where the owner is located
- vgrad - city/village where the owner is located
- moshtnost - potential power output
- vavejdane - date when the plant was built in format ddmmyy
- geo - 2/3 of the coordinates are precise and taked from the RES association. The rest are set close the the city/village marked in Ministry reports

NSI/Ekatte
------------------
Original documentation and reference tables for the Ekatte coding system by the National statistics institute
