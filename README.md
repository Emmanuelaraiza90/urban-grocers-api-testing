# urban-grocers-api-testing
REST API &amp; Integration Testing suite for Urban Grocers backend (Postman collections, JSON Schema validation, HTTP Status Codes &amp; SQL Data Persistence) - TripleTen Sprint 4.

# 🔌 Urban Grocers — API & Backend Integration Testing

![Postman](https://img.shields.io/badge/Postman-REST%20APIs-orange?style=for-the-badge&logo=postman&logoColor=white)
![SQL](https://img.shields.io/badge/Database-SQL%20Queries-blue?style=for-the-badge&logo=postgresql&logoColor=white)
![JSON](https://img.shields.io/badge/Data-JSON%20Validation-lightgrey?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

Este repositorio contiene la suite de pruebas de integración de API REST y validación de persistencia en base de datos ejecutable sobre la plataforma e-commerce **Urban Grocers**, desarrollada como parte del programa de Software Quality Assurance de TripleTen.

---

## 🎯 Objetivo del Proyecto

Validar la comunicación cliente-servidor, el cumplimiento de reglas de negocio en los endpoints del backend, la integridad de respuestas JSON y la correcta persistencia de transacciones mediante consultas SQL directas a la base de datos tras la ejecución de peticiones HTTP.

---

## 🛠️ Herramientas y Tecnologías Aplicadas

* **API Client & Testing:** Postman (Colecciones, Variables de Entorno y Ambientes).
* **Protocolo & Formatos:** REST APIs, HTTP/1.1, JSON (JavaScript Object Notation).
* **Bases de Datos & Backend:** Consultas SQL (SELECT, INSERT, UPDATE, JOINs) para verificación de persistencia.
* **Documentación Técnica:** Apidoc / OpenAPI Specifications.

---

## 🧪 Cobertura de Pruebas Realizada

* **Métodos HTTP Probados:**
  * `GET`: Recuperación de catálogos, kits de productos y parámetros de consulta.
  * `POST`: Creación de nuevos usuarios, carritos y cálculo de costos de envío.
  * `PUT`: Actualización de productos e información de kits existentes.
  * `DELETE`: Eliminación de elementos y verificación de desmantelamiento en backend.
* **Validación de Códigos de Estado (Status Codes):**
  * **200 OK / 201 Created:** Peticiones exitosas y creación de registros.
  * **400 Bad Request / 404 Not Found:** Captura de excepciones y validación de mensajes de error estructurados.
* **Persistencia en SQL:** Ejecución de consultas directas en la base de datos para confirmar que los datos enviados a través de Postman impactaron correctamente las tablas del backend.

---

## 📊 Evidencia Técnica y Documentación

Puedes consultar la matriz completa con la documentación de endpoints, pruebas positivas/negativas y enlaces a las evidencias en el siguiente enlace:

[![Ver Documentación en Google Sheets](https://img.shields.io/badge/Google%20Sheets-Ver%20Matriz%20API%20Testing-spreadsheet?style=for-the-badge&logo=google-sheets&logoColor=white&color=34A853)](https://docs.google.com/spreadsheets/d/1ZMOb8BQ79iYgn2QTDE7azsE57ZvvOEHeqg0LfOV9N2s/edit?usp=sharing)

---

## ✍️ Autor

**Jehova Emmanuel González Araiza**  
*QA Automation Engineer | Industrial Engineer*  
* [LinkedIn](https://linkedin.com/in/emmanuel-araiza-engineer)
* [GitHub](https://github.com/Emmanuelaraiza90)
