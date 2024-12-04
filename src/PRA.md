## Sauvegarde et Restauration (PRA)


**I. Généralités**

* **Pourquoi sauvegarder ?**  Prévenir la perte de données, la corruption, les sinistres.  Importance de la disponibilité des données pour la continuité de l'activité.


**II. Types de Sauvegardes**

* **Sauvegarde complète:**  Copie complète de toutes les données.  Rapide à restaurer, mais très gourmande en espace et en temps. Généralement réalisée de manière périodique, plutôt que quotidienne pour les entreprises.
* **Sauvegarde incrémentale:** Sauvegarde seulement les données modifiées depuis la dernière sauvegarde complète ou incrémentale.  Rapide, mais restauration plus complexe.
* **Sauvegarde différentielle:**  Sauvegarde seulement les données modifiées depuis la dernière sauvegarde complète. Plus rapide qu'une sauvegarde complète mais moins rapide qu'une incrémentale. Restauration nécessite la sauvegarde complète et toutes les sauvegardes différentielles.


**III. Fréquence et Planification**

* **Quand sauvegarder ?**  Optimisez les horaires de sauvegarde pour limiter les impacts sur l'activité principale. Il est souvent préférable de le faire en dehors des heures de pointe ou pendant les périodes d'inactivité.
* **À quelle fréquence sauvegarder ?**  Dépend des besoins de l'entreprise et du volume de données.  Incrémentales journalières avec complète hebdomadaire ou mensuelle sont souvent une bonne solution.
* **Stratégie de rotation:**  Rotation des sauvegardes pour gérer l'espace.


**IV. Déduplication**

* **Déduplication:**  Technique permettant de ne sauvegarder qu'une seule fois chaque donnée unique, en utilisant des identifiants uniques de tronçons de données pour économiser de l'espace.  Cette technique est utile pour les grandes quantités de données.


**V. Plan de reprise d'activité (PRA)**

* **Plan de reprise d'activité:**  Plan d'action pour restaurer les opérations d'une entreprise en cas de sinistre majeur (incendie, inondation, panne majeur, etc).  Cela inclut le choix des processus de sauvegarde et de restauration.

