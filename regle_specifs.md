#ROBOTRON REFERENCE V0.2

git du projet : https://github.com/robotronik/projet-tron


>Les règles suivantes peuvent évoluer si des failles ruinant l'expérience prévue venaient à émerger, veuillez en prendre note et l'accepter.

## REGLES

* 3 Robots évoluent sur le terrain 
* Chaque robot laisse une marque **derrière** lui lorsqu'il se déplace
* Un robot est éliminé lorsqu'il franchit une ligne, c'est à dire une ligne de délimitation extérieure du terrain ou une marque laissée par un autre robot. **La ligne est franchie si le robot passe une roue complète.**
* Un robot est éliminé en cas de collision avec un autre robot.
* Les robots sont toujours en mouvement. **NON** vous ne pouvez pas tourner sur vous même pour attendre que les autres meurent...
* Le match sera arreté après le temps imparti sauf si l'arbitre juge qu'une situation est "bloquée".
* La forme du terrain et votre position de départ est quelconque, on se concentre ici sur de l'évitement et de la détection simple.
* Les décisions de l'arbitre du match sont inconstestables.

## SPECIFICATIONS GENERALES
Votre robot comporte:
* 1 capteur ultrasons
* 4 capteur infra rouges
* 2 moteurs
* 1 chassis
* 1 support carte elec
* 1 support de feutre

références  ==> cf spreadsheet

### ELEC
Instructions précises données durant la réalisation de la carte élec avec Monsieur le président.
Une carte est fournie, l'autre sera réalisée par vous. 
Pour votre carte, il  y aura une presentation sous forme de TD ou les fonctionalites et la réalisation sera expliqué.
Cependant, la carte montré en TD est simple et peut etre amelioré pour utiliser au mieux les capteurs IR.


### MECA
Formations et instructions détaillées données prochainement lors d'une "mini conférence" d'initiation. 
Tout peut vous être fourni mais vous pouvez aussi être auteur de l'ensemble des pièces si vous le souhaitez.
On attend de vous la conception au minimum d'une pièce, tel qu'un support de carte électronique ou un support stylo. Les dimensions utiles à la conception vous serons très bientot communiquées.

UPDATE MECA : la hauteur du support carte est de 40mm et les percages de la carte elec en sont espacés de 40mm. Pour plus de renseignements 2 moyens: interroger benano et consulter le git de l'ancien projet d'itiniation ou les modèles 3D de l'ancien projet dont vous réutilisez une partie des pièces sont présents. Il y a un certains nombres de points techniques et de pièges à éviter, n'hésitez pas à vous renseigner si vous commencez à travailler avant jeudi prochain. Des explications communes seront alors données
Pour note : les cartes électroniques font 7cm * 5 cm avec des percage de 3mm à 5mm des bords si jamais vous voulez reconcevoir le support avant.

J'insiste pour avoir absolument toutes les informations et modèles 3D, consultez la partie mécanique de l'ancien projet disponible sur git https://github.com/robotronik/robot-sumo
### PROG
Vous êtes libres comme l'air(mais comme toujours vous pouvez vous tournez vers les membres du club pour de l'aide) La prog se fera sur une arduino nano.


