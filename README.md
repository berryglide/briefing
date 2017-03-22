# briefing
Briefing AC Issoudun (LFEK)


Objectif
--------
Mettre à disposition briefing vélivole où la récupération des données (MTO et information aéronautique) est automatisée.


Base de travail
---------------
Travail se basant sur ce qu'on peut trouver sur http://www.volavoile.net/index.php?showtopic=12194 et adapté pour Issoudun LFEK.


Source des données
------------------
### METAR et TAF
API https://avwx.rest/documentation, dont on peut trouver les sources pas loin d'ici : https://github.com/flyinactor91/AVWX-Engine
D'après les sources, les données sont issues de https://aviationweather.gov/adds/dataserver_current.

### NOTAM
Site web SIA : http://notamweb.aviation-civile.gouv.fr

### Cartes AZBA
Site web SIA : https://www.sia.aviation-civile.gouv.fr/schedules

### METEO
####Images satellites
API sat24 : http://api.sat24.com/
#### Sondages
Meteociel : http://www.meteociel.fr/modeles/sondage2arome.php


Reste à faire :
-------------
- Coder la récupération du SunSet, probablement en incorporant un JS utilisé ici : https://www.esrl.noaa.gov/gmd/grad/solcalc/index.html
- cartes météo : pressions, vent, analyse fronts
- Vérifier les échéances Arome pour les sondages Meteociel
...

