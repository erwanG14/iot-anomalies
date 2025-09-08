# IoT Anomalies

## 🚀 Objectif du projet
Développer une plateforme légère pour **détecter des anomalies dans des données IoT** (capteurs), avec une architecture **microservices** (Java + Python), le tout **conteneurisé** et déployé sur **Kubernetes** (Minikube en local).  

👉 But : se former aux bonnes pratiques **Data Engineering / MLOps** et construire un projet structuré et évolutif.  

---

## 🗓️ Roadmap
- **Phase 1 (MVP)**  
  - Ingestion simple de données IoT (mock)  
  - Stockage basique  
  - Microservice ML (Python, FastAPI)  
  - Endpoint anomalies disponible  

- **Phase 2 (Extensions)**  
  - Ajout de tests de charge  
  - Documentation API (OpenAPI/Swagger)  
  - Monitoring & alerting  
  - Déploiement avancé sur Kubernetes  

---

## 🏗️ Architecture (prévue)
- **Backend (Java, Spring Boot)** → API REST pour ingestion et restitution des anomalies  
- **ML Service (Python, FastAPI)** → Endpoint `/score` pour détecter les anomalies (baseline = z-score)  
- **Kubernetes (Minikube)** → Orchestration des services et scaling  
- **Docker Compose** → Développement local rapide  

---

## 📂 Structure du repo

iot-anomalies/

├── backend/ # Service Java (API Spring Boot)

├── ml/ # Service Python (FastAPI ML)

├── tools/ # Scripts utiles

├── docs/ # Documentation et schémas

├── k8s/ # Manifests Kubernetes

├── .gitignore

└── README.md

---

## ⚙️ Pré-requis
- **Java 17+**
- **Python 3.11+**
- **Docker Desktop**
- **Minikube + kubectl**
- **Git**

---

## 📌 Avancement
- ✅ Repo structuré et en ligne  
- 🔄 Currently at **J1** : mise en place du squelette de projet  
- ⏭️ Next step : premiers services (API Java + ML Python)  





