# 🛌 Análisis de Patrones de Sueño – SQL

## 📌 Descripción general

Este proyecto tiene como objetivo analizar **patrones de sueño** a partir de datos estructurados, utilizando **SQL** como tecnología principal.  
El análisis se basa en el diseño y explotación de una **base de datos relacional**, permitiendo estudiar sesiones de sueño, fases, interrupciones y factores externos que influyen en la calidad del descanso.

---

## 🎯 Objetivo del proyecto

- Diseñar un modelo de datos relacional para el análisis del sueño  
- Analizar la duración y calidad del sueño por usuario  
- Evaluar la distribución de fases de sueño  
- Identificar interrupciones y su impacto  
- Relacionar factores externos con la calidad del sueño  

---

## 🗂️ Modelado de datos

Se desarrolló un **Modelo Entidad–Relación (ER)** normalizado, que representa los principales elementos del dominio del problema.

### Entidades principales

- Usuarios  
- Dispositivos  
- Sesiones de sueño  
- Fases de sueño  
- Interrupciones  
- Factores externos  

Además, se utilizaron **tablas de referencia** para normalizar valores categóricos y reducir redundancia.

---

## 🔗 Relaciones y normalización

- Un usuario puede tener múltiples dispositivos y sesiones de sueño  
- Cada sesión de sueño puede incluir varias fases e interrupciones  
- Los factores externos se asocian a cada sesión de sueño  

El modelo utiliza **claves primarias y foráneas**, garantizando integridad referencial y consistencia de los datos.

---

## 📊 Análisis realizado con SQL

El análisis se realizó mediante consultas SQL enfocadas en:

- Duración total del sueño por usuario  
- Distribución de fases de sueño por sesión  
- Frecuencia y duración de interrupciones  
- Relación entre factores externos y calidad del sueño  
- Comparaciones entre usuarios y sesiones  

Se emplearon:

- `JOIN` entre múltiples tablas  
- Funciones de agregación (`SUM`, `AVG`, `COUNT`)  
- Filtros por usuario, fecha y condiciones externas  

---

## 🛠️ Tecnología utilizada

- **Lenguaje principal:** SQL  
- **Modelo de datos:** Relacional  
- **Enfoque:** Análisis de datos estructurados  

SQL se utilizó tanto para el diseño de la base de datos como para el análisis de la información.

---

## 🧠 Valor del proyecto

Este proyecto demuestra la capacidad de:

- Modelar un problema real mediante bases de datos relacionales  
- Aplicar normalización y relaciones correctamente  
- Analizar datos utilizando SQL  
- Extraer información relevante a partir de datos estructurados  
- Documentar y organizar un proyecto de análisis de datos  

---

## 📂 Entregables

- Diagrama Entidad–Relación  
- Scripts SQL de creación y análisis  
- Informe de resultados y conclusiones  

---

