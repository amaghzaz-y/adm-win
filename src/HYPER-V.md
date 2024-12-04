## Virtualisation de serveur avec Hyper-V

**I. Vue d'ensemble du module**

* **Concepts clés:** Hyperviseur, virtualisation de serveur, stockage d'ordinateur virtuel, réseaux virtuels.


**II. Leçon 1 : Vue d'ensemble des technologies de virtualisation**

* **Virtualisation de serveur avec Hyper-V:**  Présentation de la virtualisation de serveur.  Avantages (invisible pour les utilisateurs, flexibilité des OS, optimisation des ressources, déploiement simplifiée).
* **Windows Azure:** Plateforme de cloud computing pour l'hébergement d'ordinateurs et d'applications virtuelles.
* **Virtualisation de bureau (VDI):**  Ordinateurs virtuels accessibles via un client distant.
* **Virtualisation de présentation:**  Le serveur gère les applications et le bureau des utilisateurs.
* **Microsoft Application Virtualization (App-V):**  Isolation d'application.


**III. Leçon 2 : Implémentation d'Hyper-V**

* **Hyperviseurs de type 1 et 2:**  Différences entre les types d'hyperviseurs (noyau vs. logiciel hôte).
* **Configuration matérielle requise pour Hyper-V:**  Composants requis pour un serveur Hyper-V (processeur x64, mémoire, sous-système de stockage, débit réseau).
* **Matériel des ordinateurs virtuels:**  Configuration du matériel simulé dans un ordinateur virtuel (BIOS, mémoire, processeur, contrôleurs, cartes réseau).
* **Configuration de la mémoire dynamique:**  Configurer la mémoire allouée à l'ordinateur virtuel en fonction des besoins (mémoire vive minimale, maximale, mémoire tampon).
* **Configuration des services d'intégration:**  Configurer les services nécessaires pour gérer les fonctionnalités sur l'ordinateur virtuel (arrêt du système, synchronisation date/heure).
* **Configuration des actions de démarrage et d'arrêt:**  Choix des actions pour démarrer et arrêter automatiquement les ordinateurs virtuels (notamment en fonction du système hôte).
* **Contrôle des ressources Hyper-V:**  Supervision de l'utilisation des ressources par le serveur et les machines virtuelles.


**IV. Leçon 3 : Gestion du stockage d'ordinateur virtuel**

* **Disques durs virtuels (VHD):**  Explication des fichiers qui représentent un disque dur classique.  
* **Création de types de disques virtuels:**  Différentes façons de créer des disques virtuels (taille dynamique, taille fixe).
* **Gestion des disques durs virtuels:**  Opérations de maintenance sur les disques durs virtuels (conversion, réduction, développement).
* **Disques VHD de différenciation:**  Comment réduire l'espace disque avec les disques VHD.
* **Instantanés d'ordinateurs virtuels:**  Points de restauration dans le temps, fichier .xml pour la configuration et le disque de différenciation .avhd.


**V. Leçon 4 : Gestion des réseaux virtuels**

* **Commutateur virtuel:**  Type de réseau virtuel dans Hyper-V (externe, interne, privé).
* **Gestion des adresses MAC d'un ordinateur virtuel:**  Comment configurer et gérer les adresses MAC pour les cartes réseau virtuelles.
* **Configuration des cartes réseau virtuel:**  Gestion des paramètres de bande passante, des fonctions avancées (ex: SR-IOV).


