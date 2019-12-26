# Moteur de recommendations de films

**Description du projet**:
Un site sur le cinéma souhaite lancer un moteur de recommendations de films pour sauver les soirées ciné de leurs futurs clients.
Le seul problème est qu'il n'y a pas encore de clients, ce sera donc un moteur de recommendations de type 'content-based'.
A l'aide de méthodes non supervisées, il faudra développer une API capable de retourner 5 recommendations de films à partir d'un film 
(ou plutôt d'un id).

**Données**:
* [movie_metadata.csv](movie_metadata.csv) : Jeu de données brut (environ 5 000 films)
* [data.csv](data.csv) : Jeu de données nettoyé (utilisé dans la partie Recommendations)

**Livrables**:

*Notebooks*:
* 1_Exploration: Analyse exploratoire / Nettoyage / Traitement des variables catégorielles
* 2_Recommendations: Clustering selon différentes approches / Evaluation et comparaison

*Autres*:
* Presentation.pdf: Support de présentation en fin de projet

**API**:
Disponible sous 2 formats - remplacer \<id\> dans l'url par un chiffre (qui correspond à l'id du film recherché dans le jeu de données)
* Une version avec un format de retour JSON: [version JSON](http://weber-thomas.fr/ocr/project3/recommend/<id>)
* Une version un peu plus "friendly" avec liens vers les films proposés: [version GUI](http://weber-thomas.fr/ocr/project3/gui/recommend/<id>)