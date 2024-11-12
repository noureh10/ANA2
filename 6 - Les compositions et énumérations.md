						[[Analyse]]

# Les compositions et énumérations 
On peut utiliser d'autres types de classes, en UML, qui sont notés avec le symbole <<>>. On précise le type de données entre les chevrons. On peut soit créer une **énumération** qui contient une liste connue et limitée d'instance ou bien une **structure** qui est la modélisation d'un attribut décomposable ou composé.

Ces classes **ne peuvent pas** avoir d'associations.

Voici par exemple les quatre saisons sous forme d'énumération, un exemple plus complet est repris dans les slides.

![[Pasted image 20230218005921.png]]

Voici un exemple de classe **structure** :

![[Pasted image 20230218005952.png]]

## Association réflexive
Il existe des cas de figure ou les associations font référence à elles-mêmes, lorsqu'il y'a des liens entre objets d'une classe.

Un exemple est celui des cours, certains cours sont pré-requis d'une autre, même si ce sont des cours.

![[Pasted image 20230218005559.png]]

## Composition 
Une composition ajoute une sémantique pour pouvoir signifier qu'un objet est composé d'un autre ou bien fait partie d'un autre

- Un objet *composant* ne peut être que dans 1 seul objet *composite*
- Un objet *composant* n'existe pas sans son objet *composite*
- Si un objet composite est détruit, ses composants le sont aussi

Voici des examples de composition :

![[Pasted image 20230218010445.png]]
