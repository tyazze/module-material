# Trading Game

status : _draft_

## But : 

* Une platform de simulation boursiére.
* Accent sur le CRM et sur une architecture scalable


## Participants Groupe 1 : 

 * Camille Morand
 * Nils Ruet
 * [option data scrapping prise] Xavier Nourry
 * [option simulation prise]


## Fonctionnalitées : 
 
 * application multi-utilisateur (s'enregistrer / supprimer son compte)
 * Possibilité pour un admin de créer un ou plusieurs Jeu d'investissement (durée en nb de jours, montant initiale du portefeuille, frais de transactions, nombre de portefeuilles max par joueur)
 * Au début du jeu chaque joueur peut créer autant de portefeuille que le jeu l'autorise
 * Tous les jours ouvré la platform doit récupérer les cours de la veille et valoriser les portefeuilles
 * la platforme doit supporter tous les ordres de bourses valides (https://www.boursier.com/guide/devenir-trader-en-bourse/type-ordres-de-bourse)
 * les ordres sont évalués une fois les données de la veille actualisées  
 * la homepage anonyme comporte le classement des tournois en cours
 * la homepage du joueur lui permet de visualiser les position pour un jeu / portefeuille 
 * hors scope : on ne tient pas compte de la volatilité ni de la vente a découvert de titres

 
 
## Critères dévaluations :


Toutes les fonctionnalités sont présentes
Les contraintes techniques sont respectée
Le code est propre et les responsabilités sont correctement distribuées
La couverture de test du code java dépasse 50%
L'application est deployé via le docker-compose partagé de la classe.
L'application est polie et prête a être lancée. 


## si 3 éme membre

 * le jeu de simulation peut être lancer en 2 modes : soit live (décrit plus haut) soit historisé : le jeu commence a une date dans le passé
 * a cette fin les données historiques doivent être préchargé en base (intégralitée actions euronext paris), et le jeu configurer pour tourner sur une base de temps. (1 jours = 10 minutes)

## si 4 éme membre

 * le jeu expose une api de passage d'ordre et de gestion de portefeuil, vous coderez un client qui passera automatiquement des ordres (de jeu valident) pour des strategies simples
   ex : j achéte si j ai pas et que ca monde 3 jours de suite / je vends des que ca baisse 
