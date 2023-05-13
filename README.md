# Heuristiques-et-metaheuristiques-pour-le-Probleme-de-Sac-a-Dos-PSAD-
Ce projet contient des implémentations en Python d'une heuristique constructive, d'une heuristique de recherche locale, d'une heuristique constructive randomisée, d'une métaheuristique GRASP et d'une métaheuristique Tabou (simple) pour résoudre le Problème de Sac à Dos (PSAD).
Le PSAD est un problème d'optimisation combinatoire classique qui consiste à trouver une combinaison de N objets qui maximise la valeur totale tout en respectant une contrainte de capacité. Les approches proposées dans ce projet visent à trouver des solutions de haute qualité pour le PSAD dans un temps raisonnable.

Le code contient une procédure de lecture automatique des instances du PSAD et enregistre les résultats de chaque approche (valeur de la solution et temps d'exécution correspondant) dans un fichier Excel nommé Résultats.

Les approches implémentées dans ce projet sont :

Heuristique constructive : Cette approche permet de construire une solution initiale S0 pour le PSAD.

Heuristique de recherche locale : Cette approche utilise une structure de voisinage et une stratégie d'exploration du voisinage pour améliorer la solution initiale S0.

Heuristique constructive randomisée : Cette approche utilise une construction aléatoire pour générer une solution initiale de manière aléatoire.

Métaheuristique GRASP : Cette métaheuristique combine l'heuristique constructive randomisée avec la méthode de recherche locale proposée précédemment.

Métaheuristique Tabou (simple) : Cette métaheuristique utilise une liste tabou pour éviter de revisiter des solutions déjà explorées.
