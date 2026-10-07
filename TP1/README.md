## Etape 1

1. une machine virtuelle est une reproduction d'une machine physique mais sous forme de logiciel

2. Deux avantages de la virtualisation : 
    - Mutualisation des ressources 
    - Isolation et sécurité

3. La principale différence entre travailler dans une machine virtuelle et une machine physique c'est que cette dernière possède un materiel physique. Le temps d'accès aux ressources prends plus de temps pour une machine virtuelle puisqu'elle doivent traverser toutes les différentes couches avant d'arriver à la VM.

## Etape 2

1. Un conteneur est un espace isolé dans une machine contenant une application et ses dépendances.

2. Il n'y a pas d'OS dans un conteneur. On peut mettre des conteneurs dans des VM et pas l'inverse.

3. Parce que les conteneurs contiennet tout ce dont l'application a besoin pour fonctionner. 


## Etape 3

1. Reproductible, facile à corriger et plus rapide

2. L'image Docker sert à déployer le conteneur Docker.

## Etape 4

1. C'est plus pratique lorsqu'il y a plusieurs conteneurs. (rapidité de lancement, non omission d'étapes)

2. Il decrit toutes les étapes de lancement des conteneurs

3. Docker compose pourrait atteindre ses limites dans le cas où il y aurait énormement de conteneurs à lancer.