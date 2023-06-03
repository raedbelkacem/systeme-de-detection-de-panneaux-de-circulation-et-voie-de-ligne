# systeme-de-detection-de-panneaux-de-circulation-et-voie-de-ligne
ce systeme est integre dans une voiture comme un systeme d'aider,il est capable detecter les panneaux de circulation et de classifier. Il est aussi capable de detetcter le voie de ligne dans le but de corriger sa route
==> les etapes de  detetction de panneaux de circulation:
1) d'abort collection de donnes(des images) pour faire entrainer notre modele,apres en utilisant labelimag pour faire equiter notre modele on choisit la forme .xml
2) ensuite apre la labalisation, il faut import notre dossie de donnes dans colab en utiliser le lmien suivant: https://colab.research.google.com/github/EdjeElectronics/TensorFlow-Lite-Object-Detection-on-Android-and-Raspberry-Pi/blob/master/Train_TFLite2_Object_Detction_Model.ipynb#scrollTo=OLDnCkLLwLr6
3) enfin apres l'entrainement de modele en ulise le code detection et variation de vitess pour ouvert le camera et detetcte les panneaux de circulation 
==> on utilise le code de detection de voie de ligne pour que le voiture peut etre capable de corrige son voie
