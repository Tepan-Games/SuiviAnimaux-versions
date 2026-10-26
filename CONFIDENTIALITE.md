# Règles de confidentialité – Suivi des animaux

*Dernière mise à jour : 26 octobre 2026*

Ces règles s'appliquent à l'application Android « Suivi des animaux » (`com.tepangames.suivianimaux`)
et au logiciel Windows du même nom, édités par Tepan Games.

## Ce que l'application ne fait pas

- Elle n'envoie **aucune donnée** au développeur : pas de compte chez nous, pas de serveur, pas de statistiques d'utilisation.
- Elle ne contient **ni publicité, ni outil de suivi, ni analyse d'audience**.
- Elle ne vend et ne partage aucune donnée.

## Où sont vos données

Les informations saisies (animaux, soins, traitements, repas, stock, contacts, dépenses, photos et documents) sont
enregistrées **sur votre téléphone ou votre ordinateur**, dans le dossier privé de l'application. Chaque « espace »
(vos animaux, une association, une pension…) a son propre dossier.

### Synchronisation (facultative)

Si vous l'activez, l'application copie ces informations dans **votre propre** espace OneDrive (Microsoft) ou
Google Drive (Google), ou sur un **serveur WebDAV** que vous indiquez (NAS Synology, Nextcloud, ownCloud…),
pour les partager entre vos appareils :

- la connexion à OneDrive ou Google Drive se fait directement auprès de Microsoft ou de Google ; l'application ne voit
  jamais votre mot de passe ;
- l'accès est limité au dossier de l'application (« Suivi des animaux ») : elle ne peut ni lire ni modifier vos autres
  fichiers, sauf dans le cas du partage décrit ci-dessous ;
- pour un serveur WebDAV, l'identifiant et le mot de passe que vous saisissez servent uniquement à vous connecter à ce
  serveur ; le mot de passe est gardé chiffré sur l'appareil (Windows : protection des données de votre session ;
  Android : stockage sécurisé) et n'est jamais envoyé ailleurs ;
- les échanges sont chiffrés (HTTPS) ;
- ces copies sont soumises aux règles de confidentialité de Microsoft, de Google ou de l'hébergeur du serveur ;
- « Arrêter la synchronisation » déconnecte le compte ; vous pouvez supprimer le dossier « Suivi des animaux » de votre
  espace à tout moment.

### Partage d'un espace avec d'autres personnes (facultatif)

Quand vous **invitez quelqu'un** dans un espace (une association, par exemple) :

- le dossier OneDrive de cet espace est partagé avec le compte Microsoft de la personne, par le partage de OneDrive ;
- pour cela, et seulement à ce moment, Microsoft vous demande d'autoriser l'accès aux fichiers partagés
  (`Files.ReadWrite.All`) ; l'application ne s'en sert que pour le dossier de l'espace partagé ;
- l'invitation (lien ou QR code) contient l'emplacement du dossier, le nom de l'espace, l'adresse de la personne invitée
  et les rôles prévus ; elle ne contient **aucun mot de passe ni jeton de connexion** : la personne se connecte avec son
  propre compte ;
- l'adresse et les rôles des membres sont enregistrés dans l'espace et visibles par ses membres ;
- vous pouvez retirer un membre à tout moment : le partage OneDrive est alors supprimé.

### Base officielle des médicaments

Sur demande, l'application télécharge la base publique des médicaments vétérinaires de l'Anses (ANMV), publiée sur
data.gouv.fr. Ce téléchargement n'envoie aucune information personnelle.

### Recherche « À proximité » (facultative)

Pour trouver les vétérinaires, refuges, centres de soins et services publics autour de vous, l'application envoie
**uniquement l'adresse que vous saisissez, ou votre position si vous appuyez sur « Ma position »**, au moment de la
recherche, aux services suivants :

- la Géoplateforme de l'IGN (Base Adresse Nationale) pour trouver l'adresse ;
- l'API Recherche d'entreprises de l'État (registre INSEE) pour les cabinets vétérinaires ;
- OpenStreetMap (service Overpass) pour les vétérinaires, refuges et centres de soins ;
- TomTom (recherche de lieux) pour les numéros de téléphone ;
- l'Annuaire de l'administration (service-public.gouv.fr) pour la mairie, la gendarmerie et les services vétérinaires de l'État.

Pour afficher la carte des résultats, l'application charge le plan IGN de la zone (Géoplateforme) et la bibliothèque
d'affichage Leaflet (unpkg.com). Ces services reçoivent les demandes de la carte, comme pour toute page web, mais aucune
information sur vos animaux ni sur vous.

Aucun identifiant, nom ou donnée de vos animaux n'est envoyé. La position n'est ni enregistrée ni transmise au
développeur. Les réponses sont gardées quelques jours sur l'appareil pour ne pas refaire les mêmes recherches (celles de
TomTom seulement en mémoire, jamais enregistrées). Ces services appliquent leurs propres règles de confidentialité.

### Vigilance météo

L'accueil affiche les vigilances (canicule, grand froid, orages…) du département de la dernière adresse cherchée et des
lieux de pension de vos animaux. L'application demande pour cela la carte nationale des vigilances à Météo-France : elle
n'envoie ni adresse ni information sur vous.

### Mises à jour du logiciel Windows

Au démarrage, le logiciel Windows demande à GitHub (dépôt public Tepan-Games/SuiviAnimaux-versions) le numéro de la
dernière version. Cette demande ne contient aucune information personnelle et peut être désactivée dans les paramètres.

### Fiche d'urgence et médaille NFC

La fiche d'urgence (QR code) et la médaille NFC de collier contiennent ce que vous choisissez d'y mettre : la personne à
appeler si l'animal est trouvé et sa fiche (nom, allergies, traitements, vétérinaire…). Elles sont lisibles par
n'importe quel téléphone, sans passer par nous : ne les remettez qu'aux personnes de votre choix, ou retirez le numéro
dans les paramètres.

## Autorisations Android

- **Notifications** : rappels des prises de traitement, des soins et des repas à noter.
- **Appareil photo** : uniquement pour prendre les photos que vous ajoutez, et pour lire les codes que vous scannez
  (boîtes de médicaments, vignettes de vaccin, QR code d'invitation). Les images servant à lire un code ne sont pas enregistrées.
- **Localisation (approximative ou précise, au choix)** : uniquement quand vous appuyez sur « Ma position » dans la
  recherche « À proximité », jamais en arrière-plan. Vous pouvez la refuser et saisir une adresse à la place.
- **NFC** : uniquement quand vous écrivez une médaille de collier depuis la fiche d'urgence.
- **Internet** : synchronisation, téléchargement de la base des médicaments, recherche « À proximité » et vigilance météo.

## Suppression des données

« Plus › Vider les données de ce téléphone » efface toutes les données de l'appareil ; désinstaller
l'application les efface aussi. Sur Windows, les données sont dans `%LocalAppData%\SuiviAnimaux`. Les copies
synchronisées restent dans votre OneDrive, votre Google Drive ou sur votre serveur jusqu'à ce que vous supprimiez le
dossier « Suivi des animaux ». Un espace partagé reste chez la personne qui l'a créé.

## Enfants

L'application s'adresse aux adultes et ne collecte sciemment aucune donnée d'enfant.

## Contact

Tepan Games – tepangames@outlook.com
