## Active Directory Domain Services (AD DS)

**I. Rôles**

* **Définition:** Un rôle de serveur est un ensemble de programmes logiciels configurés pour une tâche spécifique sur un réseau (ex : serveur web, serveur de fichiers).  Les rôles définissent le but principal d'un ordinateur.

* **Fonctionnement:** Ils permettent à plusieurs utilisateurs ou ordinateurs de partager des ressources.

* **Caractéristiques:**
    * Fonction spécifique
    * Accessibilité par plusieurs utilisateurs/ordinateurs
    * Gestion de bases de données propres (ex: demandes en file d'attente, info sur les utilisateurs/ordinateurs)
    * Fonctionnement automatique une fois configurés correctement


**II. Services de Rôle**

* **Définition:** Les programmes logiciels qui permettent aux rôles d'exécuter leur fonction.  Un rôle peut avoir plusieurs services.

* **Choix:** Vous pouvez sélectionner les services nécessaires en fonction des besoins.

* **Exemple:**
    * *Serveur DNS:* un service unique.
    * *Bureau à distance:* plusieurs services (ex: accès distant).


**III. Fonctionnalités**

* **Définition:** Des programmes logiciels qui améliorent la fonctionnalité d'un ou plusieurs rôles, ou de l'ensemble du serveur.

* **Exemples:**
    * *Clustering:* améliore la redondance et les performances.
    * *Client Telnet:* permet la communication à distance.


**IV. Vue d'ensemble du module**

* **Concepts clés:**
    * AD DS
    * Contrôleurs de domaine
    * Installation de contrôleur de domaine


**V. Leçon 1 : Vue d'ensemble d'AD DS**

* **Concepts:**
    * Domaines AD DS
    * Unités d'organisation (OU)
    * Forêt AD DS
    * Schéma AD DS


**VI. Composants (Physiques et Logiques)**

* **Composants Physiques:**
    * Magasin de données
    * Contrôleurs de domaine
    * Serveur de catalogue global
    * Contrôleur de domaine lecture seule

* **Composants Logiques:**
    * Partitions
    * Schéma
    * Domaines
    * Arborescences de domaines
    * Forêts
    * Sites
    * Unités d'organisation (OU)


**VII. Leçon 2 : Vue d'ensemble des contrôleurs de domaine**

* **Concepts:**
    * Contrôleur de domaine
    * Catalogue global
    * Processus de connexion AD DS
    * Enregistrements SRV dans DNS
    * Maîtres d'opérations (FSMOs)


**VIII. Leçon 3 : Installation d'un contrôleur de domaine**

* **Méthodes:**
    * Installation à partir du Gestionnaire de serveur
    * Installation minimale Windows Server 2012
    * Mise à niveau d'un contrôleur de domaine
    * Installation à partir du support d'installation


**IX. Commandes importantes (Exemple)**

* `dcpromo /unattend:"D:\answerfile.txt"` (Installation sans assistance)

