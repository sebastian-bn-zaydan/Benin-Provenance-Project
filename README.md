# [Edo-Provenance-Project](https://sebastian-bn-zaydan.github.io/Edo-Provenance-Project/)

This project visualizes the provenance data available for artifacts stolen during the 1897 sacking of Benin city by the British military. The aim is to organize the data in an accessible manner that fascilitates research and enables activists and academics to gain new insights and organize around the cause of returning stolen artifacts to their rightful place in Benin and other countries.
ass
![alt text](https://sebastian-bn-zaydan.github.io/Edo-Provenance-Project/assets/img/epp.png "version alpha of the website")

## Structure and Design

The alpha version, published May 5t 2021, contains 100 artifacts. Additional functionality and artifcats will be added in later verions. For a specific request for additional functionality please open a git issue. The following are the main sections in this website:
* Landing Page: Contains a map with an institution slider that allows the user to focus on a particular museum. Addtionally the page also contains a preview of all the artifacts, pressign on an artifact will open information and provinance data in the artifact panel left of the map. Additionally the provinance will be mapped via pins on teh original map.
* Find page: This page allows the user to explore the collection more thoroughly, the search supports filtering by musuem, artifact category (sculpture, plaque ...), and repatriation status. Additionally, by using the search function in the top left corner of the map the user can look for artifacts by name.
* History Page: Conatins a brief history of the Benin Artifacts and teh 1897 punitive expedition, positionality statement, and a paragraph regardign the design choices made in this project.
* People and Instituions Section: visualizes the people and instituions that repeatedly appear in the provenance data.

## Backend

The provenance was collected in the [BeninArtifacts.csv file](https://raw.githubusercontent.com/sebastian-bn-zaydan/Edo-Provenance-Project/main/data/BeninArtifacts.csv) all other data files including the people and institutions csv files and all geojsons are generated from this original file by running the python script [csv2geojson in the backend folder](https://github.com/sebastian-bn-zaydan/Edo-Provenance-Project/blob/main/backend/csv2geojson.ipynb).
