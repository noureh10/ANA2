[[Analyse]]

# Les associations 1-1 et 1-N

Une association exprime une connexion durable entre classe. Plus précisément, elle permet de noter que des classes sont liées, par logique ou par choix. De plus, on veut pouvoir montrer cette liaison dans le graphe UML.

Prenons par exemple, un compte bancaire appartenant à un client. On va vouloir montrer l'association qui existe entre un client et son compte ou bien entre le compte et le client à qui il appartient. L'association doit avoir un nom descriptif et compréhensible et les rôles de chaque classe dans l'association doivent être clairement affichés.

![[Pasted image 20230218003844.png]]

Ici, il y'a plusieurs informations intéressantes, le **constructeur** de *Compte* nécessite un client mais il n'est pas repris dans les attributs de la classe. C'est parce que c'est une information redondante. En effet, en notant dans l'association qu'un compte nécessite un client, on a déja dénoté cet attribut, on ne doit pas l'afficher à nouveau. De plus, la flèche est unidirectionnelle et signifie qu'on peut seulement accéder au client depuis le compte, mais pas l'inverse.

Voici une seconde solution, bidirectionnelle.

![[Pasted image 20230218003904.png]]

Encore une fois, mes attributs qui apparaissent par l'association ne sont pas repris dans les attributs du diagramme, on évite la répétition.

Ce n'est pas tout, les objet aussi peuvent être liés. On doit donc préciser le vocabulaire. Un objet est une instance d'une classe et un lien entre objet est une instance d'une association entre classes.

Voici un court résumé : 

Diagramme d'objets | Diagramme de classses
--|--
Instances de classes | Classes
Liens entre les instances | Associations entre les classes
