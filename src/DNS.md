## Implémentation du système DNS

**I. Vue d'ensemble du module**

* **Concepts clés:** Résolution de noms, installation et gestion d'un serveur DNS, gestion des zones DNS.


**II. Leçon 1 : Résolution de noms pour les clients et les serveurs Windows**

* **Noms d'ordinateurs:**  Différents types de noms (nom d'hôte, nom NetBIOS), leurs caractéristiques et limitations.
* **DNS (Domain Name System):**  Définition de DNS et ses rôles clés dans la résolution des noms d'hôtes en adresses IP.  
* **Zones et enregistrements DNS:**  Structure des zones DNS (directes et inversées), types d'enregistrements (A, MX, SRV, NS, SOA, CNAME, PTR).
* **Résolution des noms DNS Internet:**  Processus de résolution d'un nom de domaine en adresse IP, incluant le rôle des serveurs DNS locaux, des serveurs DNS racines.
* **LLMNR (Link-Local Multicast Name Resolution):**  Méthode de résolution de noms pour les réseaux locaux qui utilise un protocole multicast.
* **Résolution des noms par un client:** Détail du processus de résolution (cache, fichier Hosts, serveurs WINS, DNS).
* **Résolution des problèmes de résolution de noms:**  Méthodes pour identifier et résoudre les problèmes liés à la résolution de noms (outils, dépannage).


**III. Leçon 2 : Installation et gestion d'un serveur DNS**

* **Composants d'une solution DNS:**  Serveurs DNS, programmes de résolution, base de données.
* **Indications de racine:**  Les informations nécessaires pour trouver les serveurs DNS racines.
* **Requêtes DNS:**  Types de requêtes (itérative, récursive) et rôle de serveurs autoritaires et non-autoritaires.
* **Transfert DNS:**  Mécanisme de partage des données DNS entre serveurs.
* **Fonctionnement de la mise en cache DNS:**  Comment un serveur DNS stocke et utilise les données de résolution de noms.
* **Installation du rôle serveur DNS:**  Processus d'installation du serveur DNS.


**IV. Leçon 3 : Gestion des zones DNS**

* **Types de zones DNS:**  Zones principales (lecture/écriture), secondaires (lecture seule), stubs (pour les serveurs externes).
* **Zones intégrées à Active Directory:**  Avantages de cette méthode (réplication, mises à jour dynamiques).
* **Mises à jour dynamiques:**  Processus de mise à jour automatique des enregistrements DNS.
* **Démonstration : Création d'une zone intégrée à Active Directory:**  Processus pratique de création d'une zone DNS intégrée dans Active Directory.
