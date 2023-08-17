# dashboard-eco

TODO :

- Prendre en main Git et Gitlab :
- 1. création d'un projet,
- 2. clonage du projet en local,
- 3.  reprise de l'architecture d'example,
- 4. adaptation avec le code existant,
- 5. push des modifications sur le dépôt partagé
- Ajouter un requirements.txt pour les dépendances et une documentation d'installation pour lancer le projet en local
- Transformer les notebooks d'extraction API et d'inférence en script python pour pouvoir les lancer en ligne de commande (voir examples d'archi dans src/scripts/)
- Si choix d'utiliser un IaaS (Infrastructure as a Service) aka Digital Ocean, AWS, Scaleway, etc... :
- 1. S'initier au scheduling avec CRON pour automatiser les scripts (possible de tester sur la machine linux local sans prendre un serveur) (https://www.adminschoice.com/crontab-quick-reference, https://crontab.guru/)

Une fois que :

- Extraction, preprocess et inférence des données automatique
- Dashboard avec les données mises à jour automatiquement

fonctionne, améliorations possibles :

- Mettre à jour les discussions existantes avec les postes récents
- Utiliser une base de données relationnelle : sqlite, postgresql, etc...
- Améliorer le code et l'architecture du projet (architecture dossiers, .env, formatteur, linter, tests, etc...)
- Améliorer le scheduling avec des logs et des alertes en cas d'erreur (voir utiliser un scheduler comme Airflow)
- Dockeriser l'application pour faciliter les déploiements
- :thinking:

Formation Bonnes Pratiques :
https://docs.google.com/presentation/d/1Qy3y0uTumQ1XIuIeYOh3FHpMqJZfrgQpIVlf1RhIE48/edit?usp=sharing