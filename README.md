<div align="right">
  <b>🇪🇸 Español</b> | <a href="https://github.com/matiasjaradev-health/hl7-translate-fhir/blob/main/README-en.md">🇬🇧 English</a>
</div>

# 🏥 HL7-TRANSLATE-FHIR

Starter Kit de interoperabilidad médica (HL7 v2 a FHIR). Middleware con Mirth Connect y servidor HAPI FHIR adaptado a la norma chilena Core-CL.

---

## 📖 Sobre el Proyecto

Este proyecto es un ecosistema de interoperabilidad clínica "listo para usar" en formato open-source. Resuelve el verdadero dolor de cabeza de los hospitales hoy: conectar sistemas antiguos que hablan HL7 v2 con plataformas modernas que exigen APIs REST en FHIR. 

El entorno orquesta herramientas estándar de la industria mediante Docker, conectando **Mirth Connect (NextGen)** con un servidor **HAPI FHIR** respaldado por **PostgreSQL**. Además, el servidor está específicamente adaptado a la Guía Core-CL oficial para cumplir con la **Ley 21.668** de interoperabilidad en Chile.

## 🚀 Guía de Inicio Rápido

### 1. Requisitos
* [Docker](https://www.docker.com/) y Docker Compose instalados en tu máquina.
* Git.

### 2. Instalación y Ejecución
Clona este repositorio y levanta los contenedores con un solo comando:

```bash
git clone [https://github.com/tu-usuario/HL7-TRANSLATE-FHIR.git](https://github.com/tu-usuario/HL7-TRANSLATE-FHIR.git)
cd HL7-TRANSLATE-FHIR
docker-compose up -d
