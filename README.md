# 🧪 QA Testing Project – Aplicación de Pedidos y Repartidores

## 📌 Descripción
Proyecto de pruebas QA enfocado en la validación funcional y de API de una aplicación de gestión de pedidos y repartidores.  
Se realizaron pruebas manuales estructuradas para identificar defectos en flujos críticos, validación de datos y lógica de negocio.

---

## 🎯 Objetivo
Garantizar la calidad del sistema mediante la ejecución de pruebas funcionales, validación de API REST y pruebas de regresión, detectando errores que afectan la experiencia del usuario y la estabilidad del sistema.

---

## 🔍 Alcance de pruebas

- Pruebas funcionales (UI y lógica de negocio)
- Pruebas exploratorias
- Pruebas de regresión
- Validación de datos de entrada
- Testing de API REST
- Validación de manejo de errores

---

## 🧪 Técnicas de testing utilizadas

- Clases de equivalencia  
- Análisis de valores límite  
- Casos positivos y negativos  
- Listas de comprobación (checklists)

---

## 🛠 Herramientas utilizadas

- Postman (API Testing)  
- Jira (gestión de bugs)  
- Excel (documentación de pruebas)  
- Chrome DevTools  
- GitHub  

---

## 📂 Estructura del proyecto

El proyecto incluye:

- ✔️ Lista de comprobación (checklist de funcionalidades)  
- ✔️ Validación de datos de entrada  
- ✔️ Casos de prueba detallados  
- ✔️ Pruebas de API (checklist de endpoints)  
- ✔️ Documentación de defectos detectados  

---

## 🔎 Funcionalidades probadas

- Registro de repartidores  
- Creación y cancelación de pedidos  
- Consulta de pedidos por track ID  
- Validación de estados de pedidos  
- Validación de campos obligatorios  
- Manejo de datos inválidos  

---

## 🐞 Resultados de testing

Durante la ejecución de pruebas se detectaron múltiples defectos, entre ellos:

- ❌ Errores en validación de datos (inputs inválidos aceptados)  
- ❌ Manejo incorrecto de estados en pedidos  
- ❌ Respuestas incorrectas en API ante datos incompletos  
- ❌ Fallos en flujos críticos del sistema  

Estos defectos fueron documentados con pasos claros de reproducción, resultados esperados vs obtenidos y evidencia.

---

## 📊 Ejemplo de bug report

**ID:** PFQA-XX  
**Título:** Error al crear pedido con datos incompletos  
**Severidad:** Alta  
**Prioridad:** Alta  

**Pasos:**
1. Enviar request de creación de pedido sin campo obligatorio  
2. Observar respuesta del sistema  

**Resultado esperado:**  
El sistema debe rechazar la solicitud con error 400  

**Resultado obtenido:**  
El sistema crea el pedido con datos incompletos  

---

## 📈 Conclusiones

El sistema presenta áreas de mejora en:

- Validación de datos  
- Manejo de errores en API  
- Consistencia en lógica de negocio  

Las pruebas realizadas permitieron identificar defectos que impactan directamente la estabilidad del sistema y la experiencia del usuario.

---

## 🚀 Habilidades demostradas

- Diseño de casos de prueba efectivos  
- Identificación y documentación de bugs  
- Validación de APIs REST  
- Análisis de requisitos  
- Testing basado en escenarios reales  

---

## 📎 Evidencia

📂 Archivo completo del proyecto:  
[https://docs.google.com/spreadsheets/d/13zkcESISmUnmBxehL_Yc6vMx-H9ORXbe/edit?usp=drive_link&ouid=100945750570669788412&rtpof=true&sd=true]

📸 (Opcional) Screenshots de pruebas o bugs

---

## 👨‍💻 Autor

**Daniel Ulises Chávez Morales**  
QA Engineer Jr  

🔗 LinkedIn: https://www.linkedin.com/in/daniel-ulises-chavez-morales/  
🔗 GitHub: https://github.com/daulises  
