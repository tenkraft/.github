# Tenkraft

## Infrastructure and Technical Stack

### Backend & Cloud  
- REST API in microservices architecture using Node.js (Express.js) and Knex.js (MySQL).  
- OIDC authentication with permission management.  
- WebSockets & MQTT for real-time communication.  
- Deployment on Kubernetes (K8s) with autoscaling and load balancing.  
- CI/CD with GitHub Actions, enabling automated deployment to the K8s cluster.

### IoT Communication  
- LoRa stack with HMAC-based encryption and dynamic key generation for secure data exchange.  
- Protocol optimization for reduced latency and low power consumption.  
- MQTT bridge between Raspberry Pi and cloud for bidirectional communication.  
- Local watchdog ensuring fallback in case of network loss.

### Edge Computing  
- Fleet of Raspberry Pi 3B running a custom Linux, executing distributed workloads.  
- Python scripts optimized for minimal CPU/RAM constraints.  
- Automated updates via GitHub + PyArmor obfuscation.  
- Centralized logging and real-time monitoring through a dedicated pipeline.

### DevOps and Orchestration  
- Service orchestration via Kubernetes with persistent volume management and dynamic scaling.  
- Fully automated CI/CD with GitHub Actions, including tests and validation before deployment.  
- Deployment on cloud cluster with automatic rollback in case of failure.  
- No direct access to production databases; all interactions go through secure APIs.

## Contact  
- support@tenkraft.com  
- [tenkraft.com](https://tenkraft.com)  

© 2025 Tenkraft - No fluff, just tech.
