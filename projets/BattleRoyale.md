# Battle Royale

status : _draft_

## But : 

* Realiser un Battle Royale Online.
* Accent sur le CRM et sur une architecture scalable


## Participants Groupe 1 : 

 * Tristan Porteries
 * Estelle Pleinet
 * [option simulation prise] Camille Ostrowski

## Participants Groupe 2 : 

 * Benjamin Verdant (1st é--è)
 * Gregory Clerc
 * [option simulation prise] Mouhammad Nour

## Fonctionnalitées : 
 
 * application multi-utilisateur (s'enregistrer / supprimer son compte / invitation par email -> enregistrement /  Social login)
 * Possibilité de Créer un Tournoi, et d'envoyer une invitation a participer a une liste d email
 * Au début de la battle chaque joueur commence avec un personnage deux boost de caractéristique (choisi) et un equipement alléatoire
 * les batailles ont lieux toutes les x minutes (configuration en db)
 * au bout de y batailles perdue un personnage est sortie du pool
 * la homepage comporte le classement du tournoi en cours xxx won over yyyy
 * un joueur ne peut avoir plusieurs personnage mais qu un personnage actif par tournoi. un meme personnage ne peut participer qu a un seul tournoi a la fois. 

 Contrainte technique _1 : On espére avoir des millions d'utilisateurs, en consequence tous les rendu doivent être pré généré
 Contrainte technique _2 : Nous souhaitons pouvoir faire évoluer les jeux tres rapidement, en conséquence on utilisera une approche evenementiel (merci de google 'Event Sourcing')
 
 ### Regles du jeux : 
 
 (précisions a venir)

 gain de caractéristiques tous les x battle gagnés
 prise d'objet a chaque bataille gagnés (aléatoire ds l inventaire du perdant)
 entre chaque bataille, possibilité pour le joueur d'utiliser ses boost et de changer 'équipement parmis son pool de matériel
 
 
 
## Critères dévaluations :


Toute les fonctionnalités sont présentes
Les contraintes techniques sont respectée
Le code est propre et les responsabilités sont correctement distribuées
La couverture de test du code java dépasse 50%
L'application est deployé via le docker-compose partagé de la classe.
L'application est polie et prête a être lancée. 


### Focntionalitées Bonus (point bonus si fonctionnalité présente et correctement implémenté): 
+ 1 : Alerte par email pour invitation au tournoi 
+ 1 : Hall of Fame des personnage et Hall of Fame des joueurs


## si 3 éme membre

un total de 5K Utilisateurs doit pouvoir être simulé, a cette fin vous écrirez un outil externe pratiquant des enregistrements et des choix de jeux.
 
