# Answers

Nom : LOBIR
Prénom : Karl-Milann

# 1.
Qu'est-ce qu'une instance EC2 ?
une instance EC2 est un serveur virtuel hébergé dans Elastic Compute Cloud, c'est un service qui permet d'éxecuter des programmes applicatifs.
Ce service peut servir de  parc  à un nombre presque illimité de machines virtuelles.
# 2.
Qu'est-ce qu'un VPC ?
Un VPC (Virtual Private Cloud) est groupe de ressources configurable à la demande dans un environnement de cloud public.
Il fournit un certain niveau d'isolement entre chaque utilisateur par l'utilisation d'un sous-réseau IP et d'un VLAN pour chaque utilisateur.

# 3.
A quoi sert un NSG ?
Un NSG (Network Security Groups) permet le contrôle du trafic entre les machines virtuelles et les sous-réseaux. Contrairement au pare-feu Windows qui est contrôlé au niveau du système d'exploitation (OS), un NSG est contrôlé au niveau de la couche réseau et est indépendant de l'OS qui tourne dans la machine virtuelle.
# 4.
Quelles sont les 5 propriétés désirables du cloud ?
La scalabilité / L'Auto-Scaling
L'Elasticité
La facilité de Backup / Restore
Le Self-Service
Le Scale to Zero
# 5.
Qu'est-ce que l'A/B Testing ?
L’A/B testing consiste à comparer deux versions d’une mise en production afin de vérifier laquelle est la plus performante. Ces variations, dénommées A et B, sont présentées de manières aléatoires aux utilisateurs. Une partie d’entre eux sera alors dirigée vers la première version tandis que l’autre sera affectée à la seconde.
# 6.
Comment programmer le cloud ?
Le cloud se programme à l'aide Web App comme Azure, AWS ou Google Cloud, permettant un déploiement rapide.
# 7.
Quelle est la technique pour faire un déploiement sans interruption de service ?
Le Blue/Green deployment est une bonne technique pour éviter l'interruption de service.

# 8.
Qu'est-ce que le Canary release ?
Le Canary release est une méthode de test pour la nouvelle version d'une Web App à déployer.
5% des utilisateurs on accès à la nouvelle version et en fonction du retour utilisateur, cette nouvelle version est soit déployée, soit patchée afin d'être re-testée ulterieurement.
# 9.
Comment changer de taille de machine virtuelle ?
Cela peut être fait manuellement sur les plateformes dédiées, on peut aussi activer l'auto-scaling (si l'option est disponible) afin de changer la taille de la machine virtuelle automatiquement.
# 10.
Qu'est-ce que le Blue/Green deployment ?
Le Blue / Green deployment consiste en un swap de redirection d'url entre deux machines, l'une étant l'ancienne version de déploiement, l'autre étant la nouvelle. Si la nouvelle version n'est pas fonctionnelle en production, alors on peut reswaper sur l'ancienne version, si la nouvelle version est fonctionnelle, alors on peut commencer à préparer le déploiement n+1 qui remplacera cette nouvelle machine.
