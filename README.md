## Context du projet
Mini projet lecteur de flux rss

Ceci est un mini projet de test pour le PROGRAMME SOFTWARE ENGINEERING EDACY - DIGITAL AFRICA
Il consiste à mettre en place un lecteur de flux RSS.

## Les besoins fonctionnels
* Récupérer le flux rss du site 'le monde' https://www.lemonde.fr/rss/en_continu.xml
* l'afficher sous un format listing avec image et extrait
* Prévoir la pagination
* Pouvoir modifier le titre
* Pouvoir modifier l'extrait

## Les contraintes
* Langage front imposé : Angular
* Langage back : au choix
* Délai : 2 jours

## Les téchnologies utilisées
### Backend (Laravel 9)
Pour le backend, j'ai utilisé le framewprk *Laravel 9

### Frontend (Angular 13.3)
Pour le frontend, c'est le framework Angular qui a été exigé

## Les processus de lancement de l'application
### backend (Laravel 9)
* Télécharger le code au format ZIP
* Décomprésser le fichier ZIP
* Ouvrir le cmd et se positionner sur le chemin du projet
* Taper "composer install"
* Ensuite taper "npm install"
* Ensuite taper "npm run dev"
* Ensuite taper "cp .env.example env" et saisisser le nom votre Base de données devant "DB_DATABASE=..."
* Ensuite taper "php artisan migrate"
* Enfin taper "php artisan serve" pour demarrer le serveur

### frontend (Angular 13.3)
* Télécharger le code au format ZIP
* Décomprésser le fichier ZIP
* Ouvrir le cmd et se positionner sur le chemin du projet
* Taper "npm install"
* Ensuite taper "ng serve"

#### Lien code backend
[code backend](https://github.com/dialloibrahimakhaliloulaye/back_rss_reader)
