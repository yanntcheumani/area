### Lauch container and app
Lancer le container :
```
docker-compose up
```
Aller sur devcontainer -> ctrl + shift + p -> Remote-containers: Open Folder in Container ....
Une fenêtre va s'ouvrir -> appuyer sur open
Ouvrer un terminal dans VScode, ca devrait etre celui du container
Aller dans le dossier 'sample' puis lancer la commande :
```
flutter run -d linux
```
Si il y a une erreur lancer :
```
flutter clean
```
Puis essayer de relancer la commande pour run
