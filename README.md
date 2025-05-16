## Description des données :
Le jeu de données collecté pour la gestion intelligente des pompes à eau comprend plusieurs variables capturées en temps réel via des capteurs IoT installés sur les pompes et dans l'environnement de la station de pompage. Les capteurs mesurent divers paramètres comme la température, l'humidité, la pression, le niveau d'eau, ainsi que d'autres facteurs environnementaux critiques qui influencent la performance des pompes. Ce jeu de données inclut également un horodatage pour suivre l'évolution des mesures dans le temps, et un statut de la machine pour indiquer si la pompe est en fonctionnement ou arrêtée.

Colonnes du jeu de données :
Unnamed: 0 : Identifiant unique pour chaque enregistrement (index).

timestamp : L'horodatage de la lecture des capteurs. Il est essentiel pour les analyses de séries temporelles et la gestion des événements sur la durée.

sensor_00 à sensor_51 : Données collectées par 52 capteurs IoT. Ces capteurs mesurent divers paramètres comme :

Température ambiante

Humidité de l'air

Niveau d'eau

Pression dans le système

Vitesse de la pompe

Autres paramètres spécifiques à l'environnement

machine_status : Le statut de la machine à la date et heure spécifiques, indiquant si la pompe fonctionne (marche) ou est arrêtée (arrêt). Cela est crucial pour la surveillance du système et les prédictions de maintenance.
