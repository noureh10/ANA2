[[Analyse]]

# Les paquets

Un paquet est un élément d'organisation qui permet de regrouper des éléments, en général on regroupe les classes, interfaces, objets, etc ; liés dans un sens logique, logiciel ou business. Un paquet donne aussi un espace de nom et touche donc à la **visibilité**. En effet, en Java par exemple, la visibilité par défaut est *package*, ce qui signifie qu'un élément n'est pas visible en dehors du paquet.

Dans un diagramme, un élément ne peut appartenir qu'a un seul paquet, mais un paquet peut en englober d'autres. Le paquet le plus englobant, c'est-à-dire au plus haut de la hiérarchie, est la racine de l'arbre des paquets.

Voici un exemple qui force un peut le trait pour faire comprendre les différents cas de figure :

![[Pasted image 20230218154936.png]]