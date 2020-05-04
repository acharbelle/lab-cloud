# 1.
Qu'est-ce qu'une instance Virtual Machine?
Il s'agit  d'une machine visrtuelle c'est à dire un ordinateur (virtiel) créé à l'intérieur d'un ordinateur réel-physique à partie de fichier informatique.
# 2.
Qu'est-ce qu'un VNET ?
Virtual Network / Réseau Virtuel est la continuité d'un réseau physique (d'une entreprise) dans le cloud.
# 3.
A quoi sert un NSG ?
Est un groupe de sécuritéde réseau, c'est donc un pare-feu de filtrage de paquets avec états qui permet de contrôler l'accès sur la base d'un algorithme à 5 tuples.
# 4.
Quelles sont les 5 propriétés désirables du cloud ?
Accès aux services par l'utilisateur à la demande
Accès à un réseau large bande
Un énorme réservoir de ressources
Un redimensionnement rapide 
Une facturation à l'usage
# 5.
Qu'est-ce que l'A/B Testing ?
Il consiste à comparer deux versions d'une page web ou d'une application afin de savoir ou de vérifier laquelle est la plus performante.
# 6.
Comment programmer le cloud ?
Il est possibil sous 3 approches:
IaaS: niveau le plus bas; pas de pile logicielle prédéfinie, tout est à y faire 
SaaS: niveau le plus élevé; il est héberger sur le site de l'éditeur. pas de brisue de bzse pour construire ses applications 
PaaS: niveau intermédiaire; il est le plus intéressant pour les développeurs car il permet de créer ses propres applications en s'appuyant sur une plateforme logicielle 
On peut également parler de l'Office Cloud qui est un niveau intermédiaire entre le PaaS et le SaaS. Elle peret de créer des suites burautiques personnalisées classiques.
# 7.
Quelle est la technique pour faire un déploiement sans interruption de service ?
Il s'agit du déploiement Blue/Green qui n'est pas très différente de celui du Canary
# 8.
Qu'est-ce que le Canary release ?
Le Canary release est un pattern qui permet de faire tester les dernières modifications réalisées à un petit nombres d'utilisateurs avent d'effectuer le déploiement général de la nouvelle version.
# 9.
Comment changer de taille de machine virtuelle ?
Dans Gestionnaire de machine, dans le menu clier sur Fichier > Gestionnaire de média
Dans l'onglet Disque dur on a la liste des disques durs gérés par Virtual box 
Sélectionner le disque dur à modifier puis afficher les Propriétés de celui-ci 
Dans l'onglet Atrributs modifier la taille du disque
Valider la modification 
Puis Fermer l'onglet 
Allouer l'espace disque supplémentaire à la partition qui en a besoin, pous se faire sous Windows utiliser l'outil intégré Gestion de disque ou sous Linux installer GParted
# 10.
Qu'est-ce que le Blue/Green deployment ?
La mise en place de deux infrastructures parallèles : Ancien - Nouvel environnement. Les équipes opérationnelles effectuent une période de test bêta afin de s'assurer du bon fonctionnement du code avant d'effectuer la transition du nombre d'utilisateursde l'ancien au nouveau. Il s'agit du déploiement Blue/Green
# 11.
Citez deux avantages du PaaS sur le IaaS ?
Plus Rapide : la solution PaaS vous permet d’économiser beaucoup de temps contrairement à la solution IaaS. Les couches de stockage, de serveurs, de virtualisation, de système d’exploitation, de middleware et de données qui sont gérés par votre fournisseur, sont disponibles immédiatement.
Innovation: cette rapidité vous apporte de l’innovation. Le PaaS vous permets de consacrer plus de temps dans le développement de vos applications et de les faire évoluer à la pointe de l’innovation.
# 12.
Quelle est la différence entre le PaaS et le Serverless ?
Serverless est moins cher que le PaaS
Serverless est plus flexible, est microgéré afin que les ressources administratives internes puissent être utilisées pour d'autres activités
Serverless offre de véritables capacités de mise à l'échelle automatique aux clients
# 13.
Que veut dire Serverless ?
Serverless en français ''sans service'' ne donne pas réellement le sens voulu. Il n'y a aucun serveur à gérer ou à provisionner du tout. C'est donc un modèle de conception et de déploiement d'applications basé sur les événements dans lequel les ressources informatiques sont fournies sous forme de services cloud évolutifs.
# 14.
Citez les trois propriétés désirable du Serverless ?
Séaparation des pouvoirs : L'un des objectifs de ce modèle est d'augmenter la productivité du développeur en s'occupant des tâches ménagères, du bootstrap et de l'environnement (les dépendances) en arrière-plan. De cette façon, du moins théoriquement, le développeur est plus libre de se concentrer sur la fonction spécifique qu'il essaie de fournir.
Sécurité améliorée : En contraignant le développeur à n'utiliser que des constructions de code qui fonctionnent dans le contexte sans serveur, il est sans doute plus probable que le développeur produise un code conforme aux meilleures pratiques et aux protocoles de sécurité et de gouvernance.
Délai de production : Le modèle de développement sans serveur vise à réduire radicalement le nombre d'étapes impliquées dans la conception, le test et le déploiement de code, dans le but de déplacer les fonctionnalités du stade de l'idée au stade de la production en jours plutôt qu'en mois.
# 15.
Comment s'appelle la plus petite unité de compute déployable en Serverless ?
Excepté l'allocation de machines virtuelles, la facturation se cale sur le temps d'exécution du code et les ressources réellement consommées. Avec la milliseconde comme unité de paiement, le serverless tient réellement les promesses du "pay as you go". En l'absence de trafic, l'utilisateur ne paie pas.
