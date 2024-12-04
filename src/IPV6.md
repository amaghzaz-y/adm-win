## Feuille de triche - Module 8 : Implémentation d'IPv6


**I. Vue d'ensemble du module**

* **Concepts clés:**  Protocole IPv6, Adressage IPv6, Cohabitation IPv4/IPv6, Technologies de transition IPv6.


**II. Leçon 1 : Vue d'ensemble du protocole IPv6**

* **Avantages d'IPv6:** Espace d'adressage plus vaste, infrastructure de routage hiérarchique, configuration sans état (ou avec état), prise en charge obligatoire d'IPsec, qualité de service (QoS), gestion améliorée des sous-réseaux, extensibilité.
* **Différences entre IPv4 et IPv6:**  La feuille de triche liste les fonctionnalités avec les méthodes utilisées dans chaque protocole.  
* **Format d'adresse IPv6:**  L'adresse IPv6 est constituée de 128 bits, représentés en hexadécimal, séparés par des deux-points.


**III. Leçon 2 : Adressage IPv6**

* **Structure de l'adresse IPv6:** Les différentes parties de l'adresse (préfixe de réseau, identificateur d'interface).
* **Adresses monodiffusion globales:**  Pour la communication sur Internet.
* **Adresses de monodiffusion uniques locales:**  Pour les communications sur des réseaux locaux.
* **Adresses de monodiffusion de liaison locale:**  Pour la communication sur des réseaux locaux.
* **Configuration automatique des adresses IPv6:**  Comment les adresses sont configurées automatiquement (ex: DHCPv6).
* **Démonstration:**  Configuration des paramètres clients IPv6.


**IV. Leçon 3 : Cohabitation avec IPv4**

* **Types de nœuds:** Nœuds IPv4, IPv6 et IPv4/IPv6.
* **Démonstration (Configuration DNS):**  Configuration du système DNS pour prendre en charge IPv6.
* **Tunneling IPv6/IPv4:**  Comment IPv6 peut être encapsulé dans des paquets IPv4 pour traverser des réseaux IPv4.


**V. Leçon 4 : Technologies de transition IPv6**

* **ISATAP:**  Un tunneling qui permet la communication IPv6 sur un réseau intranet IPv4.
* **6to4:** Un tunneling qui permet la connectivité IPv6 sur un réseau IPv4 existant.
* **Teredo:**  Un tunneling qui permet aux hôtes IPv6 de communiquer sur Internet via un serveur Teredo sur un réseau IPv4.
* **PortProxy:**  Un mécanisme de traduction de port qui permet aux applications IPv4 de communiquer avec des hôtes IPv6.
* **Processus de transition vers IPv6:**  étapes importantes pour migrer d'IPv4 vers IPv6.
