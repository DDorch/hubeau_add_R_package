# Ré-utilisations des APIs Hub'Eau, disponibles sur GitHub ou divers blogs  
## [GD4H : cas d’usage qualité de l'eau du robinet](https://github.com/blenzi/GD4H_eau)  
Le Green Data for Health (GD4H) est un projet inscrit dans le 4ème Plan National Santé Environnement qui a pour objectif de faciliter la mobilisation et la valorisation, par les chercheurs et les experts, des données environnementales au service de la santé-environnement.  
Un des cas d'usage identifiés est l'étude des impacts de la qualité de l'eau potable. 
GD4H_eau est une collection de notebooks qui illustrent la cartographie des données d’analyse de l’eau potable, en s'appuyant sur l'API qualité de l'eau potable de Hub'Eau.  
  
## [hubeau-api-wrapper javascript](https://github.com/christophe77/hubeau-api-wrapper)  
* Wrapper complet de toutes les API disponibles sur Hubeau.
* Ecrit en typescript et disponible sur [npmjs.com](https://www.npmjs.com/package/hubeau-api), il fonctionne aussi bien sur une appli backend nodejs qu'avec un framework frontend comme ReactJS.
* Des exemples ESM et CJS de chaque API sont disponibles sur le dépôt du wrapper et une démo d'utilisation avec React est [disponible ici](https://github.com/christophe77/hubeau-react-exemple).

## [Exploring (hydro-)geological data of France with python, by Guillaume Attard](https://guillaumeattard.com/exploring-hydro-geological-data-of-france-with-python/)  
The aim of this article is to present some of the webservices managed by the [French Geological Survey](https://www.brgm.fr/). Particularly, we are going to:  
* download and analyze boreholes information at the scale of the department of our choice: water supply wells and geothermal installations will be identified  
* map all this hydrogeological information on an interactive folium map and add the geological tiles of France  
* play with two Hubeau APIs to describe piezometric and physico-chemical characteristics of some groundwater wells: we will learn how to access and analyze hydraulic heads and groundwater quality fluctuations on the groundwater wells we want.

## [hubeau.py, script Python permettant d'interroger l'API hydrométrie de Hub'Eau, par Pierre-Alain Dorange](https://github.com/padorange/hubeau)  
Permet de suivre les mesures de hauteur des cours d'eau diffusée par l'API HubEau :  
* Télécharge les dernières mesures (API HubEau via le format json)  
* Stocke les mesures en local (via sqlite + sqlalchemy)  
* Permet de mettre des graphiques l'historique des hauteur d'eau (via matplotlib)  
* Génère une page HTML5+CSS+Javascript de suivi des stations de mesures (via ElementTree)  
* Intègre une carte des stations sur la page HTML via Leaflet et OpenStreetMap  
  
## [The underground French waters, by Campalo](https://github.com/Campalo/FrenchWaters)  
A French speaking user will discover the multitude of underground waters located over the French landscape. 
The user selects a departement, then sees a list of all the stations of measurement located in this specific departement, by clicking on one of the stations it displays the depth and altitude of the selected underground water station. 

## [k-hubeau, a Krawler based service to download data from French open portal Hub'Eau, by Kalisio](https://github.com/kalisio/k-hubeau)  
The **k-hubeau** jobs allow to scrape hydrometric data from the following api: [http://hubeau.eaufrance.fr/page/api-hydrometrie](http://hubeau.eaufrance.fr/page/api-hydrometrie).  The downloaded data are stored in a [MongoDB](https://www.mongodb.com/) database and more precisely in 2 collections:
* the `observations` collection stores the observed data:
  * the water level `H` in meter (m)
  * the water flow `Q` in cubic meter per second (m3/s)
* the `stations` collection stores the data of the stations

## [Timeseries forecasting use case: level of water, by Kalisio](https://github.com/kalisio/water-level-forecasting)  
> Based on Open Data provided by Hub'Eau and largely inspired by https://www.tensorflow.org/tutorials/structured_data/time_series  

Predicting the level of water in rivers can prove to be invaluable in areas with a high risk of flooding. While traditional methods are based primarily on physical model, another approach is emerging: artificial neural networks.  

## [Python & Hub'Eau, par Sofiyan Ifren](https://www.linkedin.com/pulse/python-hubeau-sofiyan-ifren/)  
Récupération de données de pêche électrique avec un peu de programmation en Python  

## [Leaflet & Hub'Eau, par Sofiyan Ifren](https://www.linkedin.com/pulse/leaflet-hubeau-sofiyan-ifren/?trk=related_artice_Leaflet%20%26amp%3Bamp%3Bamp%3B%20Hub%26amp%3Bamp%3B%2339%3BEau%20_article-card_title)  
Cartographie des données de pêche électrique avec Leaflet

## [Package R pour interroger les API Hub'Eau par David Dorchies et Pascal Irz](https://CRAN.R-project.org/package=hubeau)
Ce package publié sur le dépôt officiel CRAN facilite l'interrogation des API "Ecoulement des cours d’eau", "Hydrométrie", "Indicateurs des services", "Piézométrie", "Poisson", "Prélèvements en eau". Voir la documentation sur https://inrae.github.io/hubeau/

