## Implémentation du protocole IPv4

**I. Vue d'ensemble du module**

* **Concepts clés:** TCP/IP, Adressage IPv4, Sous-réseau, Super-réseau, Configuration et résolution de problèmes IPv4.


**II. Leçon 1 : Vue d'ensemble de TCP/IP**

* **Suite de protocoles TCP/IP:** Une suite de protocoles qui permettent la communication entre ordinateurs.
* **Protocoles de la suite TCP/IP:**  Différents protocoles (HTTP, FTP, SMTP, DNS, etc.) et leurs rôles dans la communication.
* **Applications TCP/IP:** Exemples d'applications qui utilisent la suite TCP/IP (HTTP, HTTPS, FTP, RDP, SMB, SMTP, POP3).
* **Socket:** Une combinaison d'adresse IP, de protocole de transport (TCP ou UDP) et de numéro de port pour identifier une connexion spécifique.


**III. Leçon 2 : Fonctionnement de l'adressage IPv4**

* **Adressage IPv4:** Structure et représentation des adresses IP (notation décimale avec points).
* **Adresses IPv4 publiques et privées:**  Différence et usages (ex: adresses privées pour les réseaux locaux).
* **Relation entre notation décimale et binaire:**  Conversion entre la représentation décimale (ex: 192.168.1.1) et la représentation binaire de l'adresse IP.
* **Implémentations simples d'IPv4:** Classes d'adresses (A, B, C) et leurs tailles de réseau.
* **Implémentations plus complexes d'IPv4:**  Sous-réseaux, permettant de diviser un réseau en segments plus petits.


**IV. Leçon 3 : Sous-réseau et super-réseau**

* **Sous-réseau:**  Diviser un réseau en sous-réseaux plus petits pour une meilleure gestion du trafic et de la sécurité.
* **Avantages du sous-réseau:**  Gestion du trafic, sécurité, capacité d'extension, utilisation efficiente des adresses IP.
* **Calcul des adresses de sous-réseau:**  Détermination du nombre de bits requis pour le masque de sous-réseau en fonction des besoins.
* **Calcul des adresses d'hôte:**  Déterminer le nombre d'hôtes disponibles dans un sous-réseau.
* **Création d'un modèle de sous-réseau:**  Étapes pour créer un modèle de sous-réseau adapté à un nouveau bureau.
* **Super-réseau:**  Combinaison de plusieurs petits réseaux en un seul plus grand.


**V. Leçon 4 : Configuration et résolution des problèmes liés à IPv4**

* **Configuration manuelle d'IPv4:**  Saisir manuellement les paramètres d'adresse IP, masque de sous-réseau, passerelle par défaut et serveurs DNS. (écran illustré)
* **Configuration automatique d'IPv4 (DHCP):**  Utiliser un serveur DHCP pour attribuer automatiquement les paramètres réseau. (Exemple de code)
* **Outils de résolution de problèmes:**  Commandes pour diagnostiquer les problèmes réseau (Ipconfig, Ping, Tracert, Pathping, Telnet, Netstat, Observateur d'événements).
* **Processus de résolution de problèmes IPv4:** Méthodologie de résolution des problèmes réseau.
* **Moniteur réseau:**  Outil pour capturer et analyser le trafic réseau.  (écran illustré)


**VI.  Utilisation de PowerShell (pour la configuration)**

* **Applets de commande PowerShell:**  Commandes pour la gestion d'IPv4 dans PowerShell. (Liste fournie)

