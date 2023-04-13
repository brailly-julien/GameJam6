# MedievalQuest

Pour notre workshop, nous avons dû créer un jeu type "One-push-button game". Cela consiste à ne proposer qu'un seul bouton à l'utilisateur pour utiliser l'application.

## Technologies utilisées

- Unity
- Firebase
- [Figma](https://www.figma.com/file/4LIeCOR7tFujGEYsmoDiHo/Maquette?node-id=72%3A133&t=PHTP5mSQ7tvZu6r4-1)
- Adobe Illustrator
- FL Studio 

## Principe du jeu

Nous avons fait le choix de partir sur un _infinite runner_, notre personnage se déplacera vers la droite jusqu'à ce que le joueur échoue. Il rencontrera des ennemis et des obstacles qu'il devra surpasser s'il veut survivre au travers des saisons. Pour l'accompagner dans sa quête, notre aventurier obtiendra une classe aléatoire en début de partie. Chaque classe aura des particularités propres à elle-même. Le score sera calculé à partir du nombre de jours auxquels l'aventurier aura survécu.

![image](https://user-images.githubusercontent.com/50171776/231714710-3430a3cc-d46c-41af-9b3f-fcd88b7731ac.png)
![image](https://user-images.githubusercontent.com/50171776/231714849-bed9da02-96bf-436b-bb3b-a0fa099f59f4.png)

## Travail accompli

Par manque de connaissance et de temps, nous n'avons pas pu produire toutes les fonctionnalités souhaitées. Par exemple, nous avons un lancer de dés mais celui-ci ne fournit aucun changement. Nous n'avons pas non plus eu le temps d'implémenter le système de saisons et, par conséquent, le score est calculé par la distance parcourue et non le nombre de jours. Les ennemis n'ont pas non plus été ajoutés.

Au final, nous avons un personnage qui court et qui doit éviter les obstacles et les trous afin de survivre le plus longtemps possible. Nous avons une interface proche de ce que nous voulions obtenir avec un menu de démarrage, le choix du nom, un classement (non fonctionnel) et un écran de Game Over pour pouvoir relancer une partie.

## Comment lancer l'application ?

En utilisant [Github](https://github.com/brailly-julien/GameJam6):
- Télécharger l'APK
- La copier sur le téléphone
- Trouver l'APK sur le téléphone puis exécuter.

En utilisant Firebase :
- Sur votre téléphone, suivre le [lien](https://appdistribution.firebase.dev/i/ea5fb9738c12a730) qui vous a été envoyé par mail
- Suivre les instructions officielles par Google

## Comment ouvrir le projet dans Unity

- Télécharger le zip du répertoire Github
- Ouvrir un nouveau projet
- Assets > Importer un package > Custom package
- Sélectionner "Final.unitypackage"
- Tout importer
- Faire glisser les scènes dans la hiérarchie

## Répartition des tâches

- Design, zoning, partie graphique : Clément AUPIAIS 3DIG-A et Thomas VESTIEL 3DIG-A
- Développement du jeu : Julien BRAILLY 5TEC-A, Julien DEGARDIN 4DIG-A, Amaury DELASSUS 5TEC-A
- Musique : Alexandre SCHMIDT 5TEC-A
