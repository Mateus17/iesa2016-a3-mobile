# Cours cordova

## Commandes Terminal

* Changer de répertoire : `cd ..`
* Chemin courant : `pwd`

### Commandes Cordova création d'un premier projet (mac only)

* sudo npm install -g cordova
* xcode-select --install
* sudo npm install ios-sim -g

Se rendre dans le répertoire voulu (ex: mamp/htdocs/mateus17/)

Et faire toutes ces commandes pour plus de compréhension :

* mkdir exo-01
* ls
* cd exo-01
* cordova help create
* cordova create hello ch.inagua.training.cordova "HelloWorld"
* cd hello
* ls
* cordova platform
* cordova platform add ios -save
* cordova platform ls
* cordova requirements

Si besoin :

* sudo npm install -g ios-deploy
* sudo npm install -g ios-deploy --unsafe-perm=true

* cordova requirements
* cordova build
* cordova emulate ios

### Suite :

Se rendre ici : /Applications/MAMP/htdocs/mateus17/exo-01/hello/platforms/ios puis double cliquer sur HelloWorld.xcodeproj
Faire un launch (en haut à gauche, le play). S'amuser une fois le simulateur lancé avec cmd+1, cmd+2 etc etc
