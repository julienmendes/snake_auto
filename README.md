# Apprentissage par renforcement: SNAKE

Ce script reprend le jeu snake avec pygame (source inconnue).
L'objectif est que le serpent apprenne à eviter les murs et s'éviter lui-même tout en mangeant les pommes.

Pour cela, j'ai utilisé le Q-learning.
J'ai realisé quatres matrices, chacune d'elles correspondant à la direction possible du serpent (haut, bas, droite, gauche).
ces matrices sont misent à jour par la formule: 

![formula](formula.png)

Avec s l'etat en n, s' l'etat en n+1, a l'action en n, a' l'action en n+1 et r la recompense (le score)