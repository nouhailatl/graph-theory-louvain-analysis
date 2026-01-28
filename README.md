🕸️ Analyse de Réseau Social : Détection de Communautés
Ce projet porte sur l'étude d'un réseau social composé de 18 individus. L'objectif est d'identifier des groupes cohérents (communautés) en utilisant la théorie des graphes et des méthodes algorithmiques avancées.

🚀 Objectifs du Projet
Modéliser un réseau social via une structure de graphe.

Appliquer l'algorithme de Louvain pour la détection automatique de communautés.

Analyser la qualité de la partition grâce au score de modularité.

Visualiser les interactions et les ponts entre les différents groupes sociaux.

🛠️ Installation et Prérequis
Pour exécuter le notebook, vous devez disposer de Python et installer les bibliothèques suivantes :

Bash
pip install networkx matplotlib python-louvain
📊 Analyse des Résultats
L'analyse a permis d'obtenir les résultats suivants :

Algorithme utilisé : Méthode de Louvain (Heuristique basée sur l'optimisation de la modularité).

Score de Modularité : 0.5456.

Interprétation : Un score > 0.3 indique une structure de communauté forte. Notre résultat de 0.54 confirme que les groupes identifiés (Tech, Sport, Art) sont très cohérents et bien séparés.

Visualisation : Le graphe généré affiche chaque communauté avec une couleur distincte, mettant en évidence les individus "pivots" qui connectent les différents cercles sociaux.

📁 Structure du Dépôt
graph-theory-louvain-analysis.ipynb : Le notebook contenant le code source, la génération du graphe et les calculs.

README.md : Documentation et instructions de reproduction.
