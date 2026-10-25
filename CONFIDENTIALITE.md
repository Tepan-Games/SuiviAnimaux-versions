# Règles de confidentialité – Suivi des animaux

*Dernière mise à jour : 25 octobre 2026*

Ces règles s'appliquent à l'application Android « Suivi des animaux » (`com.tepangames.suivianimaux`)
et au logiciel Windows du même nom, édités par Tepan Games.

## Ce que l'application ne fait pas

- Elle n'envoie **aucune donnée** au développeur : pas de compte chez nous, pas de serveur, pas de statistiques d'utilisation.
- Elle ne contient **ni publicité, ni outil de suivi, ni analyse d'audience**.
- Elle ne vend et ne partage aucune donnée.

## Où sont vos données

Les informations saisies (animaux, soins, traitements, stock, contacts, dépenses, photos et documents) sont
enregistrées **sur votre téléphone ou votre ordinateur**, dans le dossier privé de l'application.

### Synchronisation (facultative)

Si vous l'activez, l'application copie ces informations dans **votre propre** espace OneDrive (Microsoft)
ou Google Drive (Google), pour les partager entre vos appareils :

- la connexion se fait directement auprès de Microsoft ou de Google ; l'application ne voit jamais votre mot de passe ;
- l'accès est limité au dossier de l'application (« Suivi des animaux ») : elle ne peut ni lire ni modifier vos autres fichiers ;
- les échanges sont chiffrés (HTTPS) ;
- ces copies sont soumises aux règles de confidentialité de Microsoft ou de Google ;
- « Arrêter la synchronisation » déconnecte le compte ; vous pouvez supprimer le dossier « Suivi des animaux » de votre espace à tout moment.

### Base officielle des médicaments

Sur demande, l'application télécharge la base publique des médicaments vétérinaires de l'Anses (ANMV).
Ce téléchargement n'envoie aucune information personnelle.

### Recherche « À proximité » (facultative)

Pour trouver les vétérinaires, refuges et centres de soins autour de vous, l'application envoie **uniquement
l'adresse que vous saisissez, ou votre position si vous appuyez sur « Ma position »**, au moment de la recherche,
à des services publics et gratuits :

- la Géoplateforme de l'IGN (Base Adresse Nationale) pour trouver l'adresse ;
- l'API Recherche d'entreprises de l'État (registre INSEE) pour les cabinets vétérinaires ;
- OpenStreetMap (service Overpass) pour les vétérinaires, refuges et centres de soins.

Pour afficher la carte des résultats, l'application charge le plan IGN de la zone (Géoplateforme) et la bibliothèque
d'affichage Leaflet (unpkg.com). Ces services reçoivent les demandes de la carte, comme pour toute page web, mais aucune
information sur vos animaux ni sur vous.

Aucun identifiant, nom ou donnée de vos animaux n'est envoyé. La position n'est ni enregistrée ni transmise au
développeur ; seule la dernière adresse cherchée est gardée sur l'appareil pour la recherche suivante. Ces services
appliquent leurs propres règles de confidentialité.

## Autorisations Android

- **Notifications** : rappels des prises de traitement.
- **Appareil photo** : uniquement pour prendre les photos que vous ajoutez à la fiche d'un animal.
- **Localisation (approximative ou précise, au choix)** : uniquement quand vous appuyez sur « Ma position » dans la
  recherche « À proximité », jamais en arrière-plan. Vous pouvez la refuser et saisir une adresse à la place.
- **Internet** : synchronisation, téléchargement de la base des médicaments et recherche « À proximité ».

## Suppression des données

« Plus › Vider les données de ce téléphone » efface toutes les données de l'appareil ; désinstaller
l'application les efface aussi. Les copies synchronisées restent dans votre OneDrive ou Google Drive
jusqu'à ce que vous supprimiez le dossier « Suivi des animaux ».

## Enfants

L'application s'adresse aux adultes et ne collecte sciemment aucune donnée d'enfant.

## Contact

Tepan Games – tepangames@outlook.com
