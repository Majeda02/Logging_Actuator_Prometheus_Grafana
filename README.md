### "# Logging_Actuator_Prometheus_Grafana"

#### Objectif
Ce TP vise à doter une application Spring Boot de capacités de supervision, journalisation et monitoring comparables à celles utilisées en production dans les environnements DevOps modernes.
Il permet de :
* Collecter des indicateurs de performance (métriques, uptime, état de la JVM, requêtes HTTP, etc.) via Spring Boot Actuator.
* Exporter les données de supervision vers Prometheus pour une collecte centralisée.
* Visualiser dynamiquement ces métriques dans Grafana.
* Mettre en œuvre une journalisation structurée et configurable, pour suivre le comportement de l’application en temps réel.

#### Contexte
Dans un environnement de production, la supervision applicative est essentielle. Elle permet d’anticiper les incidents, de mesurer la charge et d’évaluer la santé du système.
Une application sans observabilité est une “boîte noire” difficile à diagnostiquer.
Spring Boot propose le module Actuator, véritable point d’entrée pour observer les performances, l’état des services et les métriques techniques.
En combinant Actuator avec Prometheus (collecteur de métriques) et Grafana (outil de visualisation), on met en place une chaîne complète d’observabilité.

#### Compétences
* Mise en place d’un monitoring complet (Actuator + Prometheus + Grafana).
* Configuration du logging structuré.
* Interprétation des métriques de performance JVM et HTTP.
* Visualisation et création de tableaux de bord dynamiques.
* Déploiement d’une architecture observable et supervisée.

#### Aspects
<img width="835" height="631" alt="image" src="https://github.com/user-attachments/assets/56916794-b2ab-4088-b9b4-afe0cb470784" />

#### Création du projet
<img width="959" height="479" alt="TP15 Creation du projet" src="https://github.com/user-attachments/assets/04ded826-ea4a-4a05-854d-46e8c150e7cc" />

#### Vérification des endpoints
<img width="959" height="473" alt="TP15_Test1" src="https://github.com/user-attachments/assets/0f169a22-d705-44b2-95b1-4be1a6f6d646" />
<img width="959" height="475" alt="TP15_Test2" src="https://github.com/user-attachments/assets/2949dbaf-453e-427d-8c8f-45f4a2cf5447" />
<img width="959" height="476" alt="TP15_Test3" src="https://github.com/user-attachments/assets/6075d186-884e-4b21-9c99-0ccbeef8c9af" />

#### Journalisation (Logging)
<img width="959" height="506" alt="TP15_log" src="https://github.com/user-attachments/assets/f6da7158-b524-44c7-82f0-5133129fcf08" />
<img width="959" height="474" alt="TP15_logProcessus" src="https://github.com/user-attachments/assets/a1d66518-f654-4e34-a04a-85589bd5501a" />
<img width="959" height="504" alt="TP15_log1" src="https://github.com/user-attachments/assets/8ba88568-d3ec-421e-8bc3-c3da0429e7f0" />

####  Prometheus
<img width="959" height="481" alt="TP15_6Prometheus" src="https://github.com/user-attachments/assets/52e67fc3-567d-47b5-84dd-a1e8c344984e" />
<img width="862" height="461" alt="TP15InstallationPrometheus" src="https://github.com/user-attachments/assets/1fa9dcfd-642a-4bd9-8f7c-abe5bd2cb382" />
<img width="959" height="478" alt="TP15AffichagePrometheus" src="https://github.com/user-attachments/assets/7aa694bb-b209-4fb9-8b93-40a99e0bb336" />
<img width="959" height="501" alt="TP15ModifierPrometheus" src="https://github.com/user-attachments/assets/e6024634-4984-4c70-8cdd-4e8d6cf7aa1a" />
<img width="959" height="479" alt="TP15ExecutionPrometheus" src="https://github.com/user-attachments/assets/461307f5-e266-4f4a-930a-b7d4e5fc916e" />

#### Grafana
<img width="959" height="474" alt="LancementGrafana" src="https://github.com/user-attachments/assets/4b981b37-d896-437a-8339-3bad903ed583" />
<img width="959" height="479" alt="dashbordGravana" src="https://github.com/user-attachments/assets/4a4fbe07-845d-4afb-872b-6877e38a8adf" />
<img width="959" height="474" alt="impoortDashboard" src="https://github.com/user-attachments/assets/8910ed6b-7b9f-4fdf-920f-276c438988fb" />
<img width="959" height="500" alt="Affichage1GrafanaHttp" src="https://github.com/user-attachments/assets/c0f85c0c-3cbe-4b98-9359-2a1342ce082b" />
<img width="959" height="470" alt="AddDATASOURCE" src="https://github.com/user-attachments/assets/cae55578-a6c3-46c8-887d-ae94ba2c9bf8" />
<img width="959" height="474" alt="AddDATASOURCE2" src="https://github.com/user-attachments/assets/e1c80ca5-9518-4321-ba3b-4bb484f9e7c6" />
<img width="959" height="469" alt="AjoutMail" src="https://github.com/user-attachments/assets/c15d41d7-80b0-4c5b-8fa2-83b702ac12e4" />
<img width="959" height="506" alt="TP15 AjoutAlerts" src="https://github.com/user-attachments/assets/f6ba7d10-c060-44cc-9af2-012866d382a6" />

#### Conteneurisation de la supervision

<img width="959" height="503" alt="Docker1TP15" src="https://github.com/user-attachments/assets/58059c14-f934-4dcf-afae-efd3d589ab65" />
<img width="1919" height="1003" alt="image" src="https://github.com/user-attachments/assets/1c937a7e-7037-4c2f-b597-ffa2f6f11838" />



