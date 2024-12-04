## Stockage, Fichiers, et Impression

**Module 9 : Stockage local**

**I. Vue d'ensemble du module**

* **Concepts clés:**  Stockage (DAS, NAS, SAN), Disques (types et performances), Volumes, systèmes de fichiers.


**II. Leçon 1 : Vue d'ensemble du Stockage**

* **Types et performances de disques:** Différences de performances et de coûts entre les types de disques (EIDE, SATA, SCSI, SAS, SSD).
* **DAS (Direct Attached Storage):** Stockage direct au serveur, peu coûteux, mais limité en disponibilité et extension.
* **NAS (Network Attached Storage):** Stockage réseau, relativement abordable, mais avec des temps d'accès plus lents.
* **SAN (Storage Area Network):** Réseau de stockage dédié, plus haut niveau de disponibilité et de redondance, plus coûteux que NAS ou DAS.
* **RAID:** Technique pour améliorer la tolérance aux pannes et les performances du stockage, utilisant plusieurs disques. Différents niveaux de RAID (ex: RAID 0, etc.).


**III. Leçon 2 : Gestion des disques et des volumes**

* **Formats de table de partition:** MBR (Master Boot Record) et GPT (GUID Partition Table).  Différences de capacité et d'utilisation.
* **Types de disques:** Disques de base et dynamiques.
* **Système de fichiers:**  Différences entre FAT, NTFS, et ReFS.  Choisir un système de fichiers adapté à vos besoins.
* **Points de montage et liens:** Créer des points de montage pour accéder aux ressources d'un disque ou répertoire autrement que par des lettres de lecteur.


**Module 10 : Services de fichiers et d'impression**

**I. Vue d'ensemble du module**

* **Concepts clés:**  Sécurisation du stockage, protection des fichiers et dossiers, configuration de l'impression réseau.


**II. Leçon 1 : Sécurisation des fichiers et des dossiers**

* **Autorisations NTFS:** Contrôle de l'accès aux fichiers et dossiers sur les volumes NTFS, incluant le concept d'héritage.
* **Dossiers partagés:**  Fonctionnement et mécanismes d'accès aux dossiers partagés (chemins UNC).
* **Énumération basée sur l'accès:**  Mécanisme pour contrôler la visibilité des dossiers partagés en fonction des autorisations.
* **Fichiers hors connexion:**  Fonctionnalité pour mettre en cache des fichiers réseau sur l'ordinateur client pour une utilisation hors connexion.
* **Démonstration:**  Création et configuration d'un dossier partagé.


**III. Leçon 2 : Protection des fichiers et des dossiers partagés à l'aide de clichés instantanés**

* **Clichés instantanés:**  Techniques de sauvegarde rapide permettant de capturer l'état des données à un instant précis.
* **Planification des clichés instantanés:** Éléments à considérer (capacité du serveur, fréquence des modifications).
* **Restauration de données à partir d'un cliché instantané:**  Comment restaurer des données à partir d'un cliché instantané.


**IV. Leçon 3 : Configuration de l'impression réseau**

* **Avantages de l'impression réseau:**  Gestion centralisée, dépannage facilité, coûts réduits.
* **Fonctionnalité Pointer & Imprimer:**  Meilleure structure de gestion pour les pilotes d'imprimante réseau.
* **Options de sécurité pour l'impression réseau:**  Autorisations permettant de contrôler l'impression.
* **Pools d'imprimantes:**  Combinaison de plusieurs imprimantes physiques en une seule unité logique.
* **Impression directe pour les filiales:**  Technique pour connecter les imprimantes du siège social aux filiales.
* **Déploiement d'imprimantes:**  Déplacer les imprimantes vers les clients.
