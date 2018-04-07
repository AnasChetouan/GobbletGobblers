# GobbletGobblers

Ce qui est fait :
- Condition de victoire (les dernières pièces de 3 cases forment une ligne de la même couleur)
- Lier le code à l'interface (renvoyer la taille, la couleur et la position à laquelle on place un carré à la souris)
- Conditions pour pas mettre un carré sur un autre plus grand
- Centrer automatiquement les pièces quand on les place
- Algorithme d'IA aléatoire

Ce qu'il reste à faire : 

- Améliorer l'algorithme pour qu'il soit + intelligent et qu'il place ses pièces en fonction de celles qui sont déjà placées

- l'IA commence dans tous les cas: placer une grosse pièce au milieu

- Mode défense : Si le joueur a deux pièces alignées alors l'IA couvre la plus grose 
avec sa plus grosse pièce disponible
Si c'est pas possible : compléter la ligne avec sa plus grosse pièce
Si c'est pas possible : Passer en mode Attaque


- Mode attaque : Placer la plus grosse pièce qu'il a sur une ligne où il a posé le + de pièces et où il peut soit couvrir une pièce soit en poser une directement et s'il peut rien faire -> placer au hasard


