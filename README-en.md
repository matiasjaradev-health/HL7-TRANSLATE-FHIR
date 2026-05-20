<div align="right">
  <a href="README.md">🇪🇸 Español</a> | <b>🇬🇧 English</b>
</div>

# 🏥 HL7-TRANSLATE-FHIR 🇨🇱

**English:** Healthcare interoperability starter kit (HL7 v2 to FHIR). Middleware using Mirth Connect and a HAPI FHIR server adapted to the Chilean Core-CL standard.

---

## 📖 About the Project

This project is a "ready-to-use" clinical interoperability ecosystem in an open-source format. It solves the real-world headache facing hospitals today: bridging legacy systems that speak HL7 v2 with modern platforms requiring FHIR REST APIs. 

The environment orchestrates industry-standard tools using Docker, connecting **Mirth Connect (NextGen)** with a **HAPI FHIR** server backed by **PostgreSQL**. Furthermore, the server is specifically adapted to the official Core-CL Implementation Guide to comply with Chile's clinical interoperability **Law 21.668**.

## 🚀 Quick Start Guide

### 1. Requirements
* [Docker](https://www.docker.com/) and Docker Compose installed on your machine.
* Git.

### 2. Installation and Execution
Clone this repository and spin up the containers with a single command:

```bash
git clone [https://github.com/tu-usuario/HL7-TRANSLATE-FHIR.git](https://github.com/tu-usuario/HL7-TRANSLATE-FHIR.git)
cd HL7-TRANSLATE-FHIR
docker-compose up -d
