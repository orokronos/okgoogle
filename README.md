# okgoogle

l'objectif est d'allumer une led en donnant l'instruction a google assistant

## liste des composants et materiel necessaire
+ un arduino esp32
+ un breadboard 
+ 1 led
+ 1 resistance 220hom
+ 1 pc sous ubuntu
+ 1 compte IFTTT service internet qui permet de creer une interface iot
+ 1 compte webhook relay  service internet permet de connecte ifttt avec node-red
+ Node-Red
+ 1 serveur mosca

## MONTAGE

monter une led et la resistance sur la breadboard et connecté au esp32

## Photo du montage

## Mise En Place des Services

sur mon pc demarer le serveur mosca
declarer le port usb de l'arduino (si tu sais pas va voir sur le gestionnaire de port de l'ide apres avoir cabler l'arduino)

televerser le code arduino du github
essayer d'allumer la led en envoyer des message MQTT a partir d'un terminal ubuntu
commande pour envoyer un message   1=led on 0=led of
ouvrir IFTT creer une nouvelle applet suivre les etape
choisir la case google assistant
arriver a choise service choissir la tuile webhook
une fois fini clique sur make a web request
aller sur webhook ouvrir un beqquet copier le lien attribuer
le mettre dans la page IFTT rester ouverte
aller dans red nod mettre les briques
dans la brique webhooi mettre les toker attribuer par le site
ca marche

