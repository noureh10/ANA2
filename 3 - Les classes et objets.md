[[Analyse]]

# Les classes et objets

Pour cette section, nous nous concentrons sur une description de la structure et non plus du comportement. En décrivant les classes et les objets.

## Classe 
Une classe décrit un concept général dans le sens du code, comme une Vidéo,un Point, etc. De nombreux exemples sont repris dans les slides et dans le cours de DEV2.

Ce qui nous intéresse est qu'une classe est une déclaration d'état et via des attributs et de comportement via des méthodes, on les sépare par une ligne. Attention, on ne décrit pas le comportement de la méthode elle même, ce n'est pas le role du diagramme de classe. Pour tous les attributs et méthodes, on y attachera un **type** qui permet de les décrire, aussi la **visibilité** est importante.

Les membres (attribut ou méthode) publics sont notés par un +, ceux qui sont protégés par un #, privés par un - et package par un ~.

Voici un exemple avec une classe *Compte* avec une note précisant une contraine, on peut aussi utiliser des traits.

![[Pasted image 20230217233408.png]]

## Objet

Un objet est un élément du monde réel, là ou une classe est plus proche d'un plan ou d'un concept. De ce fait, les objets ont des valeurs attribuées à leur état ce qui n'est pas le cas des classes.

De manière générale, un objet sera une *occurrence** ou une *instance* d'une classe. Là ou la classe est l'idée général, un objet est une réalisation de cette idée avec des valeurs qu'on lui attribue. La classe spécifie la structure et l'objet est une création qui suit cette structure.

Voici un exemple de classe *Compte*, instanciée via un objet *monCompte*.

![[Pasted image 20230217233736.png]]

Ici, on remarque que les valeurs des attributs sont précisées mais qu'on ne donne pas les méthodes, en effet le comportement de l'objet est défini par sa classe, il n'est pas précisé à nouveau dans l'UML de l'objet