# DAN-P8-Etude-eau-potable-avec-Tableau.  
## Lien Tableau public:  
https://public.tableau.com/app/profile/benali1717/viz/etudeeaupotable/Histoire1?publish=yes![image](https://github.com/BahiaB/DAN-P8-Etude-eau-potable-avec-Tableau/assets/94194381/b6ccf3d9-363a-40ae-8239-a2af4c6e918c). 
## Présentation du projet
DWFA est une ONG dont l’ambition est de fournir un accès à l’eau potable à tout le monde.
Les domaines d’expertises sont:
	- Le consulting.
	- La création de nouveaux services.
	- La modernisation de services déjà existants.
Afin de définir le prochain projet dans lequel DWFA va s'engager, l'ONG a besoin d'indicateurs calculés à l'échelle nationale pour les trois domaines d'expertise.


Afin de déterminer sur quel domaine d'expertise se basera le prochain projet de DWFA, il est important de comprendre l'état général de l'accès à l'eau potable à l'échelle mondiale et régionale. Pour ce faire, il est nécessaire de prendre en compte plusieurs indicateurs clés, tels que:
La mortalité dû à de l’eau insalubre.
La répartition des populations (Rural, Urbaine).
La stabilité politique.
L’accès des populations aux services de base. 
L’évolution de ces indicateurs a travers les années (2000-2017)

Ces indicateurs permettront également de déterminer les pays qui sont confrontés aux difficultés les plus importantes en matière d'accès à l'eau potable.

## Traitement des données
Le pré-traitement des données à été effectué dans un notebook Jupyter.
Les principales opérations qui ont étés faites sont:
	- La suppression de certaines colonnes et ligne. Afin de ne garder que 	 	   les indicateurs qui  serons utilisés lors de l’analyse.
	-  Ajout d’une colonne avec le % calculé par pays du taux de la 	  	   population habitant en zone urbaine.
	- Une succession de fusion entre les différents fichiers.
	- Exportation du nouveau data frame sous forme de fichier CSV

À la fin du pré-traitement  il ne reste qu’un seul fichier comprenant tout les indicateurs qui vont pouvoir ensuite être analysés avec Tableau.




