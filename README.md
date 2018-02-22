# swarmAura
biological inspirate swarm technology for resilient, temporary, light, microrobot architecture, sharing devices information P2P , osFree

osLess : Souveraineté et liberté
 
Penser l'écosysteme numérique sans les OS (systéme d’exploitation) , Barebone.
 
Aujourd'hui les gigantesques clouds de google sont l'image de la façon dont le web est devenu, hypercentralisé, "market-driven" et nous dépossédant de notre liberté dans le réseau, et mettant à mal notre souveraineté. Pour sortir de cet dépendance et de cet ennui, je me suis inspiré de mon background de biologiste pour proposer une infrastructure permettant l'émergence de nouveaux comportements des logiciels, des humains, des robots, en gros des utilisateurs.

Envisager les "devices" (téléphones, serveur, frigo, voiture connectés), non pas comme des entités uniquement, mais comme des extensions,  de ressources cpu, mémoire, micro, webcam partageables et donc  monayables.
 
On peut en envisager dans les villes, des bornes de ressources matérielles, cpu, mémoires sur lesquels vos devices maitres peuvent se connecter et avec lesquels ils peuvent collaborer. Votre voitures, un drone, un robot, des capteurs.  Ils seraient équipé d'un os minimal extremement léger,  (une sorte de docker).

   
Technologie : Docker+iPXE+massivement parallèle pour fournir un OS on-the-fly.
- Technologie déja bien connue, des microkernels, et une installation wifi PXE : http://ipxe.org/start
- Le microkernel est un os minimal qui  peut même être stocké en mémoire.
- Le PXE permet de faire un boot depuis le réseau.
- Le stockage in-memory permet de laisser moins de traces, diskless

 

Avantages :
- Souplesse
- Massivement décentralisé et distribué
- Plus Sécurisé
- Indépendant
- Capital en cas de guerre
- Si on coupe google on fait quoi, si on coupe amazon ? 30% du cloud dans le monde.

 

Désavantages :
- Nécessite un temps de déploiement et de l'énergie consommé
- Config à recharger à chaque fois

 
 
 
1-Scénario 1 : (le moins intéressant):
Vous rentrez chez vous ou vous prenez votre voiture, vous êtes capable d'importer votre config qui se trouve sur un disk san wireless qui est sur une clé usb wireless (raspberry zero), qui est dans votre poche  sur tout vous appareils,  sur votre téléphone, des configs mises à jours, depuis des dépots locaux, la conf de votre frigo, de vos robots ménages, le controleur des stores, votre voiture sont mis à jour automatiquement .....
 

 4-Bot MarketPlace :
 Une place de marché (décentralisées ou pas ) ou les robots, IA, peuvent récupérer des ressources pour gagner en performances
 
 

 

 Scénarios à développer 

 
 
 2-Scénario 1 :
Un robot est capable de déployer un environnement sur les devices amis qui sont dans sont environnement immédiats, pour l'aider à faire des calculs, lui permettre d'augmenter sont périmétre  d'écoute, de vus, des drones en mode client-serveur, half-duplex, ou whatever :), c’est du swarm, une nuée d’appareilles collaborants.




3-Scénario 2

Une écosysteme permettant l'émergence de nouvelles formes de programmes plus indépendants (WORMs intelligents (virus inoffensif support d’IA non liée à une infrastructure),
indépendants, mouvants, capables de contrer skynet; :D
 

Scénario  non-hostile


Environnement 

Ensemble hétérogène de machines connectées à un point d’accés wifi
Scénario de type Twin  Evil
Point Zéro [device infecté avec access SUDO] conecté à ce réseau: 


Actions 

Création d’un environnement Propice
Sniff Réseau, Déauth, Remplacement du point d’access wifi, basculement de tout les devices connectés de l’ancien réseau au nouveau réseau.

Propagation des particules Virals 
Propagation des particules virales puis exécution en mode daemon sur les machines connecté au Réseau Propice.

Début du cycle non-dormant 
Organogénese en fonction des capacités de chaque device.
Sur les téléphones portables on considérera le daemon comme cellules sexuels, ou graines.
Les yeux quand il y a caméra, oreille micro etc ...
Cerveau pour la machine la plus puissante du réseau etc ....
Déploiement des modéle de réseau de neurones. En fonction des  Deamon/Device


