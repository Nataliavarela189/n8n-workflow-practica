# 🤖 Automatización de Datos con n8n + API REST + PostgreSQL

Sistema de automatización para extracción, procesamiento y almacenamiento de datos utilizando n8n, integración con APIs REST y persistencia en PostgreSQL.

---

## 🧩 Descripción

Este proyecto implementa un flujo automatizado que:

1. Consume datos desde una API REST
2. Procesa y transforma la información
3. Almacena los resultados en una base de datos PostgreSQL

Está orientado a simular un pipeline de datos real, aplicando conceptos de automatización y backend.

---

## 🔄 Flujo de trabajo

* Trigger automático o manual en n8n
* Llamado a API externa
* Transformación de datos (filtrado, mapeo, validaciones)
* Inserción en base de datos PostgreSQL

---

## 🚀 Funcionalidades

* Consumo de API REST
* Automatización de tareas con n8n
* Transformación de datos
* Persistencia en PostgreSQL
* Manejo de errores en el flujo
* Logging básico del proceso

---

## 🏗️ Arquitectura

* **n8n** como motor de automatización
* **API REST** como fuente de datos
* **PostgreSQL** como almacenamiento
* Flujo desacoplado y escalable

---

## 💻 Tecnologías

* n8n
* API REST
* PostgreSQL

---

## ▶️ Ejecución del proyecto

### 1. Levantar n8n

```bash id="1f9q3b"
npx n8n
```

### 2. Configurar workflow

* Importar el workflow JSON incluido en el repositorio
* Configurar credenciales de API
* Configurar conexión a PostgreSQL

### 3. Ejecutar flujo

* Ejecutar manualmente desde n8n
  o
* Configurar trigger automático (cron)

---

## 🗂️ Estructura del proyecto

* `/workflows` → definición del flujo de n8n
* `/db` → scripts de creación de tablas
* `/docs` → documentación adicional

---

## 🧠 Conceptos aplicados

* Automatización de procesos
* Integración con APIs
* ETL (Extract, Transform, Load)
* Persistencia de datos
* Manejo de flujos y errores

---

## 🎯 Objetivo

Demostrar habilidades en automatización e integración de sistemas, simulando un flujo de datos real utilizado en entornos empresariales.

---

## 📈 Posibles mejoras

* Orquestación con múltiples workflows
* Manejo avanzado de errores y reintentos
* Dashboard de monitoreo
* Integración con servicios cloud (AWS / GCP)
* Notificaciones (email / Slack)

---

## 👩‍💻 Autor

Natalia Varela
