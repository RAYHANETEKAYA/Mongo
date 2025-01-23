# TP 1 

Ce TP permet de récupérer les données en temps réel des stations Vélib' via l'API et de les insérer dans une base de données MongoDB. Les données sont mises à jour toutes les minutes pour garantir leur fraîcheur.

## Fonctionnalités

- **Récupération des données des stations Vélib'** : Le projet interroge l'API pour récupérer les informations des stations Vélib' en temps réel.
- **Insertion dans MongoDB** : Les données récupérées sont stockées dans une base de données MongoDB afin d'être facilement consultées et analysées.
- **Mise à jour périodique** : Les données sont mises à jour toutes les minutes, garantissant qu'elles sont toujours à jour.
# TP 2

Ce TP interroge l'API pour récupérer des informations sur les stations Vélib'. Il affiche une carte interactive à l'aide de la bibliothèque Python **Folium**, où chaque station est représentée par un marqueur. Lorsque l'utilisateur clique sur un marqueur, un **popup** contenant des informations détaillées sur la station s'affiche.

Les informations affichées dans le popup incluent :

- **Nom de la station** : Le nom de la station Vélib'.
- **Capacité** : Le nombre total de vélos que la station peut accueillir.
- **Vélos disponibles** : Le nombre de vélos disponibles à la station.
- **Vélos mécaniques** : Le nombre de vélos mécaniques disponibles.
- **Vélos électriques** : Le nombre de vélos électriques disponibles.






