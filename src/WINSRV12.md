## Déploiement et Gestion Windows Server 2012

**Module 1 : Aperçu et Configuration Initiale**

* **Aperçu de Windows Server 2012 :**
    * **Serveurs Locaux :** Fournissent des ressources (fichiers, impression, etc.) aux périphériques clients.
    * **Cloud Computing :** IaaS, PaaS, SaaS. Les clouds privés sont généralement sur site, mono-locataire et hautement automatisés via System Center 2012.
    * **Éditions :** Standard, Datacenter, Foundation, Essentials, Hyper-V Server, Storage Server (Workgroup & Standard), MultiPoint Server (Standard & Premium).
    * **Interface minimale du serveur :** Option d'installation sécurisée et économe en ressources, gérable via `sconfig.cmd` ou PowerShell, idéale pour la gestion à distance.
    * **Rôles :** Serveur Web, Contrôleur de domaine, Serveur de certificats, etc. Les rôles contiennent des composants de services de rôle qui fournissent des fonctionnalités spécifiques.
    * **Fonctionnalités :** Prennent en charge les rôles de serveur (par exemple, Sauvegarde Windows Server, clustering). Certaines fonctionnalités sont installées à la demande à partir d'une image montée.

* **Administration de Windows Server 2012 :**
    * **Gestionnaire de serveur :** Gérez plusieurs serveurs à partir d'une seule console, ajoutez des rôles/fonctionnalités, lancez PowerShell, affichez les événements, configurez les paramètres, exécutez l'Analyseur des meilleures pratiques.
    * **Outils d'administration :** Centre d'administration Active Directory, console DNS, Observateur d'événements, Gestion des stratégies de groupe, Gestionnaire des services Internet (IIS), Analyseur de performances, Moniteur de ressources, Planificateur de tâches.
    * **Gestion à distance :** WinRM pour la gestion par ligne de commande/PowerShell, Bureau à distance pour les sessions graphiques.

* **Installation :**
    * **Méthodes :** Disque optique, clé USB, Services de déploiement Windows.
    * **Types :** Mise à niveau (conserve les fichiers et les paramètres), Personnalisée (installation propre).
    * **Configuration minimale requise :** Processeur x64 (1,4 GHz), 512 Mo de RAM, 32 Go d'espace disque (plus si RAM > 16 Go).

* **Configuration post-installation :**
    * **Paramètres réseau :** Configurez l'adresse IP, le serveur DNS.
    * **Jonction de domaine :** Nécessite un nom de domaine et un compte autorisé. La jonction de domaine hors ligne utilise `djoin`.
    * **Activation :** Utilisez la clé de produit.
    * **Configuration de l'interface minimale :** Utilisez `sconfig.cmd` pour gérer les paramètres.

**Module 2 : Introduction à Windows PowerShell**

* **Qu'est-ce que PowerShell ?** Un framework d'automatisation des tâches et de gestion de la configuration.
* **Syntaxe :**
    * `Get-Command -Noun <NomNom>` : Découvrir les cmdlets liées à un domaine spécifique (par exemple, Service, EventLog, Process).
    * `Get-Command -Verb <NomVerbe>` : Découvrir les cmdlets qui effectuent une action spécifique (par exemple, Get, Set, New).
    * `Help <NomCmdlet>` ou `Get-Help <NomCmdlet>` : Obtenir des informations d'aide sur une cmdlet spécifique.
* **Cmdlets courantes pour l'administration de serveur :**  Concentrez-vous sur les cmdlets utilisant des noms comme  `Service`, `EventLog` et `Process`.
* **Module ServerManager :** Fournit des cmdlets pour la gestion des rôles et des fonctionnalités du serveur (par exemple, `Get-WindowsFeature`, `Install-WindowsFeature`).
* **PowerShell ISE :** Un environnement de script intégré pour l'écriture, l'exécution et le débogage de scripts PowerShell.