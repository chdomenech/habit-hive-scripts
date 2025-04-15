# habit-hive-scripts

# 📋 HabitHive – Plan de Desarrollo Semanal

Este documento contiene la planificación paso a paso para construir el proyecto HabitHive desde cero, en 2 semanas con una dedicación diaria de 3–4 horas.

---

## ✅ Semana 1: Backend, Infraestructura y Preparación

### 🔹 Día 0–1: Setup Inicial
- [ ] Leer y anotar objetivos del proyecto.
- [ ] Crear documento en Notion o Google Docs con:
  - [ ] Lista de funcionalidades mínimas.
  - [ ] Cronograma editable.
- [ ] Instalar herramientas:
  - [ ] Java 17+
  - [ ] Node.js y Angular CLI
  - [ ] AWS CLI
  - [ ] Serverless Framework
  - [ ] Git + GitHub Desktop o CLI
- [ ] Crear repositorio `backend-habithive`
- [ ] Configurar IDE (IntelliJ recomendado)
- [ ] Configurar Trello / GitHub Projects

---

### 🔹 Día 2–4: Infraestructura Backend Inicial
- [ ] Estructurar proyecto en carpetas:
  - `/src`, `/test`, `/infra`, `/docs`
- [ ] Crear Lambda “Hello World” en Java con Serverless Framework.
- [ ] Configurar API Gateway y exponer la función como endpoint.
- [ ] Habilitar logs y métricas en CloudWatch.
- [ ] Añadir instrucciones de uso en `README.md`.

---

### 🔹 Día 5–7: Lógica y Modelo de Datos
- [ ] Diseñar modelo de datos en DynamoDB:
  - [ ] Usuario
  - [ ] Hábito
  - [ ] Estado
- [ ] Implementar funciones:
  - [ ] POST /habits
  - [ ] GET /habits
  - [ ] PUT /habits/{id}
  - [ ] DELETE /habits/{id}
- [ ] Añadir pruebas unitarias básicas.
- [ ] Documentar los endpoints.

---

## ✅ Semana 2: Frontend, Integración y Despliegue

### 🔹 Día 8–9: Desarrollo Angular Inicial
- [ ] Crear repo `frontend-habithive`
- [ ] Crear proyecto Angular
- [ ] Crear componentes:
  - `HabitListComponent`
  - `HabitFormComponent`
  - `StatsDashboardComponent`
- [ ] Crear servicios Angular para llamar al backend

---

### 🔹 Día 10–11: Integración y Despliegue Frontend
- [ ] Conectar servicios Angular con API real.
- [ ] Manejo de errores y validaciones básicas.
- [ ] Configurar despliegue:
  - [ ] Subir app a S3
  - [ ] Configurar CloudFront
- [ ] Pruebas básicas de navegación y consumo real de API.

---

### 🔹 Día 12–14: Pruebas, Ajustes y Documentación
- [ ] Pruebas end-to-end frontend ↔ backend.
- [ ] Ajustes en UI/UX (colores, feedback, mensajes).
- [ ] Crear documentación técnica:
  - [ ] Estructura del proyecto
  - [ ] Endpoints
  - [ ] Instrucciones de despliegue
- [ ] Definir hoja de ruta futura:
  - Integración IA
  - Migración a CloudFormation
