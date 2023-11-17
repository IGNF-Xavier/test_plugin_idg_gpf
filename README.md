# Test pour plugin IDG avec services de la Géoplateforme
Plugin pour QGIS 3 fournissant un accès simple aux données de l'ensemble des Infrastructures de Données Géographiques (IDG) et d'autres ressources nationales géographiques utiles.
Test sur les services de la Géoplateforme.

Pré-requis :
- QGIS version LTR [3.28] ou supérieure
- Une connexion Internet
- Installation depuis fichier zip : dans le gestionnaire d'exentions (Extensions > Installer/Gérer les extensions), activer les extensions expérimentales et rechercher le plugin IDG au format zip sur son ordinateur


Notes : 
- Le plugin idg-0.2.2 (https://github.com/geo2france/idg-qgis-plugin) est non fonctionnel cherchant indéfiniment les serveurs.
- Utilisation de idg-0.2.1
  - modification du fichier tree_node_factory.py pour charger le fichier default_idg.json depuis ce Github avec la fonction download_default_idg_list
  - modification de default_idg.json pour référencer le projet Qgz projet_idg_gpf.qgz 
- Le fichier idg.zip intègre ces modifications

 

