\# 🤖 Robo-Courier City (Projet V16)



\*\*Projet d'Algorithmique Avancée \& Robotique\*\*

\*Simulation de tournées de livraison optimisées dans une ville modélisée par un graphe.\*



---



\## 📋 Description du Projet



Ce projet modélise une ville sous forme de graphe pondéré où un robot-coursier doit livrer plusieurs colis en optimisant son trajet\[cite: 2, 4].L'application permet de visualiser les algorithmes de recherche de chemin en temps réel et de comparer leurs performances\[cite: 19, 20].



Cette version finale (\*\*V16\*\*) intègre des contraintes réalistes avancées telles que la capacité limitée du véhicule et des événements imprévus (manifestations/risques)



\## ✨ Fonctionnalités Principales



\### 1. Algorithmes de Recherche 

\* \*\*Dijkstra :\*\* Exploration uniforme garantissant le chemin optimal.

\* \*\*A\* (A-Star) :\*\* Recherche guidée par heuristique.

&nbsp;   \* \*Heuristiques incluses :\* Distance Euclidienne et Distance de Manhattan.



\### 2. Planification de Tournée

\* \*\*Stratégie Gloutonne (Nearest Neighbor) :\*\* Le robot recalcule dynamiquement la destination la plus proche à chaque étape.

\* \*\*Gestion des retours :\*\* Retour automatique au dépôt en fin de tournée.



\### 3. Extensions Modulaires (Activables/Désactivables) 

\* \*\*📦 Capacité Limitée (VRP) :\*\* Le robot possède une capacité de chargement maximale. Il retourne au dépôt pour recharger lorsque son coffre est vide.

\* \*\*🚧 Gestion des Risques :\*\* Simulation d'événements aléatoires (grèves, manifestations) augmentant le coût de traversée de certaines zones.



\### 4. Interface \& Visualisation

\* \*\*Suivi Visuel :\*\* Un point noir (●) représente le robot se déplaçant sur les arêtes.

\* \*\*Mode Comparatif ("Both") :\*\* Exécution simultanée de Dijkstra et A\* pour comparer visuellement l'exploration.

\* \*\*Statistiques :\*\* Affichage dans le terminal du temps de calcul, coût total, nœuds explorés et visités.

\* \*\*Contrôle :\*\* Bouton Pause et fermeture via la touche `Echap`.



---



\## 🛠️ Prérequis et Installation



Le projet nécessite \*\*Python 3\*\* et les librairies suivantes.



1\.  Assurez-vous d'avoir Python installé.

2\.  Installez les dépendances via pip :



```bash

pip install matplotlib networkx

