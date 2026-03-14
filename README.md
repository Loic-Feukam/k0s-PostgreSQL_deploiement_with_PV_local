# Déploiement de PostgreSQL sur Kubernetes en utilisant un volume local (localhost) pour la persistance des données

Dans ce cas, les données de la BDD sont stockées directement sur la machine qui héberge le cluster Kubernetes.



  **Architecture**


L’architecture repose sur les composants suivants :

* Un Pod PostgreSQL déployé dans Kubernetes (with single-node).

* Un PersistentVolume (PV).

* Un PersistentVolumeClaim (PVC).

