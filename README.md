# PyManager
![banner_PyManager](banner.png)
Application Windows (PyQt5) pour voir, ajouter et gérer les installations Python de ton ordinateur 
et leurs bibliothèques (pip).

# Fonctionnalités
. Détection de python.exe s'il trouve 
. interagir les librarys pour sois réparé/mettre a jours ou déinstaller 
. Réparation du pip s'il y'a un problème en rapport PyManager  demmande de reinstaller le pip en cas de sousis
. Modifiable vous pouvez mettre des raccourcis (Bureau / menu Démarrer) + 10 langues prévus dans l'icon paramaètre 

# Racine de Chemin 
Tout les fichier créer à coté du l'application ou ( APPDATA\PyManager si le dossier n'est pas modifiable)

### Fichier	Contenu
`settings.json`	Thème et langue choisis
`pythons.json`	Python ajoutés / retirés manuellement
`pip_install.log`	Journal des installations de pip (utile en cas d'échec)

### Langue 
Choix dans Paramètres → Langue : Français, English, Español, Deutsch, Português, Italiano, Nederlands, Русский, 中文, 日本語. 
Au premier lancement, la langue de Windows est utilisée si elle fait partie de la liste (sinon l'anglais). Après un changement, 
PyManager propose de redémarrer.

# Dépannage
### Problème                             Solution
Le bouton Réinstalle pip n'apparait pas / Il n'existe que pour les Python embeddable `python3xx._pt`
Un Python ** Microsoft Store ** n'apparaît pas /	Installe-le depuis le Store : seuls les Python réellement installés sont listés
