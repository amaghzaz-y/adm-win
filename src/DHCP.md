## Feuille de triche - Module 6 : Implémentation du protocole DHCP


**I. Vue d'ensemble du module**

* **Concepts clés:** Installation d'un serveur DHCP, configuration des étendues DHCP, gestion des bases de données DHCP, sécurisation et surveillance du service DHCP.


**II. Leçon 1 : Installation d'un rôle Serveur DHCP**

* **Avantages de DHCP:** Simplification de la configuration des adresses IP, automatisation des tâches administratives, réduction des erreurs de configuration.
* **Fonctionnement de l'allocation d'adresses IP par DHCP:**  Le processus de requête, offre, demande et réponse pour l'attribution d'une adresse IP.
* **Fonctionnement du processus de création d'un bail DHCP:** Étapes du processus de création d'un bail DHCP (DHCPDISCOVER, DHCPOFFER, DHCPREQUEST, DHCPACK). Diagrammes illustratifs.
* **Fonctionnement du processus de renouvellement d'un bail DHCP:** Étapes du processus de renouvellement d'un bail DHCP (DHCPREQUEST, DHCPACK). Diagrammes illustratifs.
* **Agent de relais DHCP:**  Un routeur ou un ordinateur qui transmet les requêtes des clients DHCP aux serveurs DHCP sur des sous-réseaux différents.
* **Autorisation du serveur DHCP:**  Comment configurer le serveur DHCP dans Active Directory pour qu'il soit autorisé à attribuer des adresses IP.
* **Démonstration : Ajout du rôle serveur DHCP:**  Processus de mise en place d'un serveur DHCP.


**III. Leçon 2 : Configuration des étendues DHCP**

* **Étendues DHCP:**  Un ensemble d'adresses IP que le serveur DHCP peut attribuer aux clients.
* **Réservations DHCP:**  Attribution d'une adresse IP spécifique à un client DHCP particulier.
* **Options DHCP:**  Paramètres supplémentaires qui peuvent être configurés pour ajuster le fonctionnement du serveur DHCP (ex: passerelle par défaut, serveurs DNS, serveurs WINS).
* **Application des options DHCP:**  Comment les options DHCP sont appliquées au niveau du serveur, de l'étendue, de la classe et du client réservé.
* **Démonstration : Création et configuration d'une étendue DHCP:** Processus pratique de création et de configuration d'une étendue DHCP.


**IV. Leçon 3 : Gestion d'une base de données DHCP**

* **Base de données DHCP:**  Description des informations stockées dans la base de données DHCP (étendues, réservations, baux).
* **Sauvegarde et restauration de la base de données DHCP:**  Importance de sauvegarder la base de données et les méthodes de restauration.
* **Rapprochement d'une base de données DHCP:**  Processus permettant de mettre à jour la base de données avec les données les plus récentes.
* **Déplacement d'une base de données DHCP:**  Procédure de déplacement d'une base de données DHCP vers un nouveau serveur.


**V. Leçon 4 : Sécurisation et surveillance DHCP**

* **Sécurisation DHCP:**  Procédures pour empêcher les ordinateurs non autorisés d'obtenir des baux et les serveurs non autorisés de louer des adresses IP.
* **Délégation de l'administration DHCP:**  Délégation des responsabilités d'administration.
* **Statistiques DHCP:**  Informations sur l'utilisation, les demandes et les problèmes relatifs au serveur DHCP.
* **Journal d'audit DHCP:**  Informations détaillées sur les événements et les actions DHCP.
* **Problèmes DHCP courants:**  Dépannage des problèmes courants (conflit d'adresses, échec d'obtention d'adresse).


