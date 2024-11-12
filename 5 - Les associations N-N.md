[[Analyse]]

# Les associations N-N

Une association n'est pas toujours de type 1 pour 1 comme montré dans la partie précédente, on peut avoir des associations plus nombreuses. La multiplicité désigne le nombre d'objets qui peuvent participer à une association.

Les multiplicités dépendent du contexte et doivent couvrir tous les cas possibles, elles sont notées en général :

- Synthaxe : {min} .. {max}
- 0..1
- 1..1 ou 1
- 0..n ou 0..* ou *
- 1..n ou 1..*

![[Pasted image 20230218004940.png]]

Voici un exemple avec le jeu Memlory réalisé en DEV2. Un Memory a bien un et un jeu (Game), un jeu comporte autant de cartes qu'on veut.