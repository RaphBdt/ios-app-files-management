# Notes

D’ordre général les composants du Framework UIKit sont composés d’une View et d’un Controller.

## Table View

C’est un composant d’interface qui permet d’afficher une liste de données. Il est relié à un **TableView**, un **TableViewCell** et un **TableViewController**.

D’ordre général les composants du Framework UIKit sont composés d’une **View** et d’un **Controller**.

Le View est le composant qui va afficher les données et le Controller est le composant qui va gérer les données et les actions de l’utilisateur. Ils sont préfixés par UI pour indiquer qu’ils font partie du Framework UIKit.

Il y a donc 3 composants pour implémenter TableView :
- TableView : C’est le composant qui va afficher la liste de données
- TableViewCell : C’est le composant qui va être répété pour chaque élément de la liste
- TableViewController : C’est le composant qui va gérer les données et les actions de l’utilisateur

### Ajouter Table View au projet

Il faut taper la commande `CMD + Shift + L` et il faut le glisser dans la vue principalen de l'application. 

***On peut supprimer la View Controller par défaut***
