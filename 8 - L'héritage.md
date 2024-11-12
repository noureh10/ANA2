[[Analyse]]

# L'héritage
L'héritage est un principe de la programmation orientée objet ou une classe (enfant) étend une autre classe (parent), en héritant de ses membres. On peut ainsi créer des arbres de liaisons entre classes? La classification entre des classes pour savoir qui hérite de qui n'est pas toujours évidente, il faut donc être explicite sur les choix qu'on fait.

L'association d'héritage se réalise entre classes et ne porte pas de nom ni n'a de multiplicité, elle est notée par une flèche, de l'enfant vers le parent. Une proposition équivalente à l'héritage est de dire qu'on "est" la classe dont on hérite. Par exemple, une classe *Pizza* qui hérite de *RepasItalien* permet de dire qu'on est une pizza et aussi un repas italien. Une classe *Spaghetti* héritant elle aussi de *RepaisItalien* est un plat italien, mais pas une pizza. On peut le voir sous la forme suivante.

![[Pasted image 20230218011629.png]]

Comme les enfants héritent des comportements des parents, on ne doit pas réécrire les membres du parent chez l'enfant. Cependant, si on décide de redéfinir un membre dans une sous-classse, alors on doit réécrire ce membre. Ceci permet de montrer qu'une même méthode se comporte différemment suivant la classe à laquelle elle appartient, on parlera de **polymorphisme**. Attention, une classe ne peut **pas** hériter d'elle-même et l'héritage ne peut pas créer de cycle.

Dans l'exemple suivant, les classes enfants ont les mêmes membres que la classe parent. La classe E par contre redéfini l'unique méthode de la super-classe A. En pratique, ce diagramme signifie que des instances des sous-classes de A peuvent avoir un lien avec des instances de D. En effet, B, C, et E sont tous des enfants de A et donc en hérite à créer une association avec D.

![[Pasted image 20230218153144.png]]

Aussi, il est important de remarquer que l'héritage n'apparaît que dans les diagrammes de classes. Les objets n'ont pas de liens explicites pour démontrer l'héritage, un lien est bien une instance d'une association, pas d'un héritage. Donc, au moment de la représentation,  aucun lien n'apparaît pour désigner l'héritage des objets.