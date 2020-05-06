# 1.
Qu'est-ce qu'une instance Virtual Machine ?

Une machine virtuelle, ou VM (Virtual Machine), est un environnement d'application ou de système d'exploitation (OS, Operating System) installé sur un logiciel qui imite un matériel dédié. Côté utilisateur final, l'interaction avec une machine virtuelle est la même qu'avec un matériel dédié.

# 2.
Qu'est-ce qu'un VNET ?

VNET signifit Virtual Network (Réseau Virtuel). Il permet à un réseau de centres de données de fournir une structure de réseau la plus appropriée et la plus efficace pour les applications qu'il héberge. Il permet aussi de modifier cette structure selon les conditions, en utilisant un logiciel au lieu de faire des changements physiques dans les connexions au matériel. C’est la continuité du réseau physique d’une entreprise, mais dans le cloud.

# 3.
A quoi sert un NSG ?

Le Network Security Group s’applique sur:

Cartes réseaux/serveurs
Base de données
Passerelle VPN
Sous réseau
Tag/balise 

# 4.
Quelles sont les 5 propriétés désirables du cloud ?

Les cinq caractéristiques essentielles du Cloud computing :

Accès aux services par l’utilisateur à la demande
Accès réseau large bande
Réservoir de ressources (non localisées) 
Redimensionnement rapide (élasticité) 
Facturation à l'usage

# 5.
Qu'est-ce que l'A/B Testing ?

L’A/B Testing est une technique qui consiste à mettre en comparaison deux versions d’une page web, d’une application, d’un e-mail ou même d’un formulaire, afin d’analyser les résultats et déterminer la version la plus performante selon l’objectif souhaité

# 6.
Comment programmer le cloud ?

Les étapes pour programmer le cloud sont : stocker les données transférer les applications dans le cloud disposer d’une visibilité complète faire des amélioration

# 7.
Quelle est la technique pour faire un déploiement sans interruption de service ?

Pour faire un déploiement sans interruption de service, il faut isoler les machines de productions, découper les versions en plusieurs livraisons petites et moins complexes, automatiser les étapes de tests et passages en production d’une nouvelle version pour réduire les cycles.

# 8.
Qu'est-ce que le Canary release ?

Le canary release est un pattern qui permet de faire tester les dernières modifications réalisées (appelée version N+1) à une tranche de population restreinte avant de réaliser un déploiement général de cette version.

# 9.
Comment changer de taille de machine virtuelle ?

VBoxManage.exe modifyhd "D:\VirtualBox\Windows 10bis.vdi" --resize 500000. Ici on augmente le disque dur de 500Go.

# 10.
Qu'est-ce que le Blue/Green deployment ?

Le Blue Green deployment est un modèle de publication d'application qui permet de transférer progressivement le trafic utilisateur depuis la version antérieure d'une application ou d'un micro-service vers une nouvelle version pratiquement identique. Ces deux versions s'exécutent en même temps dans l'environnement de production. L'ancienne version représente l'environnement bleu, tandis que la nouvelle version représente l'environnement vert. Une fois que le transfert du trafic entre l'environnement bleu et l'environnement vert est achevé, l'ancienne version peut être conservée pour une nouvelle restauration, ou peut être retirée de l'environnement de production

# 11.
Citez deux avantages du PaaS sur le IaaS ?

Une mise en production quasi instantanée. Une fluidité dans l'organisation

# 12.
Quelle est la différence entre le PaaS et le Serverless ?

Les applications Serverless évoluent instantanément, automatiquement et à la demande, sans configuration supplémentaire de la part du développeur ou du fournisseur. En revanche, ce n'est pas une caractéristique intrinsèque de PaaS. Le serverless peut évoluer rapidement en faisant tourner de nouvelles instances de fonctions d'application à mesure qu'elles sont demandées. Il se réduit également rapidement en arrêtant les fonctions lorsqu'elles ne sont plus nécessaires ou lorsqu'elles ont fonctionné pendant une période de temps définie. Les applications basées sur PaaS ne peuvent pas évoluer si rapidement ou à un tel degré.    

# 13.
Que veut dire Serverless ?

Le serverless est un modèle de cloud computing dans lequel le fournisseur de serveur gère les ressources attribuées au service client. Cela signifie sans serveur.

# 14.
Citez les trois propriétés désirable du Serverless ?

 Une application Web Serverless peut évoluer jusqu'à arrêter son activité, puis redémarrer en réponse à un événement en quelques secondes ou millisecondes. Certains fournisseurs Serverless ne facturent aux développeurs que la durée exacte d'exécution de leurs fonctions. Le temps de lancement des applications Serverless est très rapide.

# 15.
Comment s'appelle la plus petite unité de compute déployable en Serverless ?

La plus petite unité de compute déployable en Serverless est une fonction (programme informatique)