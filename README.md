# Windows-update

## Ne peut plus booter
Message francais : "Échec de la configuration des mises à jour de windows annulation des modifications"
Message anglais : "Failure configuring Windows updates. Reverting changes"

Solution trouvée : 
https://www.thewindowsclub.com/failure-configuring-windows-updates

F8

Réparer

Depuis la console, aller dans lecteur Windows (celui qui contient le profil attendu), renommer les dossiers suivants (move) :
C:\\Windows\\WinSxS et C:\\Windows\\SoftwareDistribution\\* (tous ses fichiers et dossiers)

Redémarrer
