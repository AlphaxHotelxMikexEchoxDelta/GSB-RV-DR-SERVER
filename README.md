# GSB-RV-DR-SERVER
server Rest pour l'apllication [GSB RV DR](https://github.com/AlphaxHotelxMikexEchoxDelta/GSB-RV-DR) ( [du projet Galaxy Swiss Gourdin](https://github.com/AlphaxHotelxMikexEchoxDelta/GSB-Projet) )

## Installer les ressources
```bash
apt install python3 pip mariadb-server
pip install flask mysql.connector
```

## Installation de la base de donnees
placez vous dans le dossier ```GSB-RV-DR-SERVER```, puis connectez vous a mariadb
```bash
mariadb -h {host} -u {utilisateur} -p
```
ensuite lancez les commandes suivante
```
source BD/GSB-RV.sql ;
```

## Lancez le server avec ```python3 App/appRV-Visiteur.py```
