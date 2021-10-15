# Windows-update

## Ne peut plus booter
Message francais : "Échec de la configuration des mises à jour de windows annulation des modifications"

Message anglais : "Failure configuring Windows updates. Reverting changes"

Solution trouvée : 
https://www.thewindowsclub.com/failure-configuring-windows-updates

1. F8
1. Réparer
1. Depuis la console, aller dans lecteur Windows (celui qui contient le profil attendu), renommer les dossiers suivants (move) :
   1. C:\\Windows\\WinSxS
   1. C:\\Windows\\SoftwareDistribution\\* (tous ses fichiers et dossiers)
1. Redémarrer
