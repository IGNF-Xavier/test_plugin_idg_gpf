# Test pour plugin IDG avec services de la Géoplateforme
- Le plugin idg-0.2.2 (https://github.com/geo2france/idg-qgis-plugin) est non fonctionnel cherchant indéfiniment les serveurs.
- Utilisation de idg-0.2.1
  - modification du fichier tree_node_factory.py pour charger le fichier default_idg.json depuis ce Github avec la fonction download_default_idg_list
  - modification de default_idg.json pour référencer le projet Qgz projet_idg_gpf.qgz 
- Le fichier idg.zip intègre ces modifications
  - à installer dans Qgis par le menu "Installer/gérer les extensions" => Installer depuis un fichier Zip
  - Le menu IDG apparait ensuite dans le menu explorer de Qgis
 
A la différence d'un projet Qgis avec l'ensemble des couches, le menu IDG ne charge que les couches choisis par l'utilisateur dans l'espace de travail Qgis
