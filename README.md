Description
Ce script Bash permet de synchroniser un fichier ou un répertoire entre deux emplacements spécifiés. Il prend en compte divers scénarios de conflit, tels que les différences de métadonnées, les conflits entre répertoires et fichiers, et la gestion des liens symboliques.

Fonctionnalités
Validation des répertoires : Vérifie que les répertoires spécifiés existent et sont uniques dans l'arborescence du système.
Gestion des fichiers : Supporte la synchronisation des fichiers ordinaires et des répertoires.
Gestion des conflits : Résout les conflits en fonction des métadonnées des fichiers et propose des options pour renommer ou déplacer des fichiers/répertoires.
Journalisation : Enregistre les opérations de synchronisation dans un fichier journal.
Utilisation
Préparation :

Assurez-vous que le script a les permissions d'exécution : chmod +x script.sh.
Préparez un fichier journal nommé journal pour enregistrer les opérations.
Exécution du Script :

Lancez le script avec la commande suivante : ./script.sh.
Saisie des Informations :

Vous serez invité à entrer les noms des deux répertoires à synchroniser ainsi que le nom du fichier ou du répertoire à synchroniser entre eux.
Modes de Synchronisation :

Mode simple : Synchronise les fichiers ou répertoires en copiant les éléments d'un emplacement à l'autre.
Mode avec comparaison du contenu : Compare le contenu des fichiers pour détecter des différences et les gérer en conséquence.
Gestion des Conflits :

Le script gère les conflits possibles, y compris les différences de contenu et de métadonnées, et propose des options pour résoudre les conflits en renommer ou déplacer des fichiers/répertoires.
Exemples
Pour synchroniser deux répertoires contenant un fichier spécifique :


./script.sh
Suivez les instructions pour entrer les noms des répertoires et du fichier à synchroniser. Choisissez le mode de synchronisation lorsqu'on vous le demande.

Notes
Le script suppose que les répertoires spécifiés sont uniques dans l'arborescence du système.
Les conflits entre répertoires et fichiers sont gérés en proposant des options pour renommer ou déplacer les éléments concernés.
Le fichier journal est utilisé pour suivre les opérations et les métadonnées des fichiers synchronisés.

Auteur
PIAHA Sun
