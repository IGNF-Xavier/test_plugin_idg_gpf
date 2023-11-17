# Test pour plugin IDG avec services de la Géoplateforme
- Le plugin idg-0.2.2 est non fonctionnel.
- Utilisation de idg-0.2.1
  - modification du fichier tree_node_factory.py pour charger le fichier default_idg.json depuis ce Github avec la fonction download_default_idg_list
  - modification de default_idg.json pour référencer le projet Qgz projet_idg_gpf.qgz 
- Le fichier idg.zip intègre ces modifications et peut dès lors installé dans Qgis par le menu "Installer/gérer les extensions" => Installer depuis un fichier Zip
