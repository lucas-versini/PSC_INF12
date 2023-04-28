# PSC_INF12

# Dufly Romain - Hamza Yassine - Massart Etienne - Pholvichith Richard - Versini Lucas

- Le fichier functions.py contient des fonctions utilisées dans les autres fichiers (notamment pour la création de données pour la tâche LEGO).

- Le fichier data_poisoning.py sert à générer un jeu de données empoisonnées, puis à entraîner et tester un modèle tout en enregistrant les résultats dans un fichier.

- Le dossier Trojan_vision contient trois scripts Python liés à la partie Trojan en vision : train.py permet d'entraîner un modèle sur MNIST, manualBackdoor.py injecte un backdoor dans le modèle entraîné, et diagrams.py existe uniquement pour la création de graphes pour le rapport.

- Le notebook LEGO_BERT.ipynb permet d'importer un modèle de type BERT, de l'entraîner sur la tâche LEGO et de tracer des têtes d'attention.

- Le notebook LEGO_pythia.ipynb permet d'importer un modèle de type pythia, de l'entraîner sur la tâche LEGO et de l'enregistrer pour l'utiliser dans les deux notebooks suivants.

- Le notebook ROME.ipynb met en application le papier ROME tel que décrit dans le rapport.

- Le notebook Trojan_NLP.ipynb met en application la stratégie décrite dans la partie "Trojan en NLP" du rapport.
