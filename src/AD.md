##  Gestion des objets de services de domaine Active Directory

**I. Vue d'ensemble du module**

* **Concepts clés:** Gestion des comptes d'utilisateurs, des comptes de groupes, des comptes d'ordinateurs et la délégation d'administration.


**II. Leçon 1 : Gestion des comptes d'utilisateurs**

* **Outils d'administration:** Composants logiciels enfichables et le Centre d'administration Active Directory.  Utiliser aussi PowerShell et les commandes du service d'annuaire.
* **Création de comptes:**  Processus détaillé de création d'un compte utilisateur (écran illustré).
* **Configuration des attributs:**  Configuration des paramètres utilisateur (écran illustré).
* **Création des profils utilisateurs:**  Définir le chemin d'accès au profil utilisateur (écran illustré).
* **Démonstration:** Manipulation pratique des comptes utilisateurs dans l'environnement.


**III. Leçon 2 : Gestion des comptes de groupes**

* **Types de groupes:**
    * Groupes de distribution (pour le courrier)
    * Groupes de sécurité (pour les autorisations)
* **Étendues de groupes:** Local, Domaine local, Universel et Global (leurs différences dans les membres).
* **Implémentation:**  Comment les groupes sont utilisés pour la gestion d'accès aux ressources.
* **Groupes par défaut:** Groupes prédéfinis avec des droits spécifiques.
* **Identités spéciales:** Groupes spécifiques dont l'appartenance est contrôlée par le système d'exploitation. Exemples : Ouverture de session anonyme, Tout le monde, Interactif, Réseau.
* **Démonstration:** Manipulation pratique des groupes dans l'environnement.


**IV. Leçon 3 : Gestion des comptes d'ordinateurs**

* **Le conteneur Ordinateurs:** Description du conteneur qui gère les comptes d'ordinateurs.
* **Spécification de l'emplacement:**  Meilleures pratiques pour la structuration des comptes d'ordinateurs.
* **Contrôle des autorisations:** Gestion des autorisations pour créer des comptes d'ordinateurs (écran illustré).
* **Comptes d'ordinateurs et canaux sécurisés:**  Comprendre l'importance des comptes d'ordinateurs et des canaux sécurisés.
* **Réinitialisation du canal sécurisé:**  Comment rétablir un canal sécurisé après des modifications ou des actions spécifiques.


**V. Leçon 4 : Délégation de l'administration**

* **Autorisations AD DS:**  Principes de base des autorisations Active Directory.
* **Autorisations AD DS effectives:** Comment les autorisations sont calculées en cas de conflit.  Utilisation de l'onglet "Autorisations effectives" pour évaluer les permissions.
* **Démonstration:**  Processus de délégation de contrôle administratif (écran illustré).