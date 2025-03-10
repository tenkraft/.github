# Tenkraft

## Infrastructure et Stack Technique

### Backend & Cloud  
- API REST en microservices avec Node.js (Express.js) et Knex.js (MySQL).  
- Authentification OIDC avec gestion des permissions.  
- Websockets & MQTT pour communication en temps réel.  
- Déploiement sur Kubernetes (K8s) avec autoscaling et load balancing.  
- CI/CD via GitHub Actions avec déploiement automatisé sur cluster K8s.

### Communication IoT  
- Stack LoRa avec mécanisme de chiffrement basé sur HMAC et génération de clés dynamiques pour sécuriser les échanges.
- Optimisation protocolaire pour latence réduite et faible consommation énergétique.  
- Bridge MQTT entre Raspberry Pi et cloud pour communication bidirectionnelle.  
- Watchdog local assurant un fallback en cas de perte réseau.

### Edge Computing  
- Fleet de Raspberry Pi 3B sous Linux customisé, exécutant des workloads distribués.  
- Scripts Python optimisés pour contrainte CPU/RAM minimale.  
- Automatisation des mises à jour via GitHub + obfuscation PyArmor.  
- Logs centralisés et monitoring en temps réel via pipeline dédié.

### DevOps et Orchestration  
- Orchestration des services via Kubernetes avec gestion des volumes persistants et scaling dynamique.  
- CI/CD entièrement automatisé avec GitHub Actions, incluant tests et validation avant déploiement.  
- Déploiement sur cluster cloud avec rollback automatique en cas d’échec.  
- Aucun accès direct aux bases de données en production, tout passe par des API sécurisées.

## Contact  
- support@tenkraft.com  
- [tenkraft.com](https://tenkraft.com)  

© 2025 Tenkraft - No fluff, just tech.
