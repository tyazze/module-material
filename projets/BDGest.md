# BD Gest

status : _draft_


## But : 

* Realiser une application de gestion de collection de bande dessinée.


## Participants Groupe 1: 

 * Hamze Al-Rasheed
 * Robin Wagner
 * [option Scrapping de data] : Bertrand Passieux
 * [option client Android] :

## Participants Groupe 2: 

 * Martin Folliet
 * Yoan Ameloot
 * [option data scrapping prise] : Tristan Delapierre
 * [option client android prise] : Nicolas Commandeur

## Participants Groupe 3: 

 * Hamza Mahri
 * Visar Sylejmani
 * [option data scrapping prise] :
 * [option client android prise] :

 
## Fonctionnalitées : 
 
 * application mutli-utilisateur (s'enregistrer / supprimer son compte)
 * je peux visualiser une album (ISBN, titre, image série, numéro d'ordre pour la série), une série (liste des albums appartenant a la série par ordre dans la série)
 * je peux rechercher des bandes dessinée par auteur / série / titre / isbn, 
 * je peux marquer un album comm faisant partie de ma collection
 * je peux marquer une série, un auteur comme suivie.
 * ma home page indique : le nombre ainsi  que les 5 premiéres séries 
 

 
## Critére dévaluations :

Data :  devront être importé dans l'application les séries : 
 Arcanes (Pecau)
 Arcanes Majeures (Pecau)
 Travis
(sauf si option data scrapping)

toute les fonctionnalitées sont présentes
le catalogue est cacheable sur un cdn
le code est propre et les responsabilitées sont correctement distribuées
le couverture de test du code java dépasse 50%

l'application est deployé sur le docker-compose de la classe.

l application est production ready. 


### Focntionalitées Bonus (point bonus si fonctionnalité présente et correctement implémenté): 
+ 3 : je peux partager ma collection en lecture seule a travers un qr code 
+ 2 : je peux marquer un album comme prété (a date, a quelqu'un)


## si 3 éme membre

un total de 5K BD doit être chargé dans la base, a cette fin vous ecrirai un outil de scrapping du site web de votre choix.
cette fonctionalité doit être accessible via une page d'admin et presenter la date du dernier import et le nombre de nouvelles BD importées 
 
## si 4 éme membre

toute les fonctionalitées hors imports doivent être disponible a travers une applciation android.
