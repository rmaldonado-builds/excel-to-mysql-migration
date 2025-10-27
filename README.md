# 📊 Migración Excel a MySQL - Contact Center Campaign

![MySQL](https://img.shields.io/badge/MySQL-8.0-4479A1?logo=mysql&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?logo=microsoftexcel&logoColor=white)
![Status](https://img.shields.io/badge/Status-En_Desarrollo-yellow)

> Proyecto de migración de un informe real (anonimizado) de empresa de contact center, especializado en campaña de emisión y evaluación de calidad del servicio.

---

## 📋 Descripción del Proyecto

Este proyecto documenta el proceso completo de transformación de un **seguimiento operativo en Excel** (usado diariamente en entorno empresarial real) hacia una **base de datos relacional en MySQL**.

### 🎯 Objetivos

- ✅ Demostrar habilidades de **análisis y modelado de datos**
- ✅ Aplicar **normalización de bases de datos** (formas normales)
- ✅ Crear **estructura de base de datos profesional** desde cero
- ✅ Implementar **scripts SQL reutilizables y documentados**
- ✅ Transformar datos operativos en información estructurada

### 🏢 Contexto del Proyecto

**Origen de datos:** Informe real de una empresa de contact center  
**Tipo de campaña:** Emisión de llamadas (outbound)  
**Propósito:** Evaluación de calidad del servicio al cliente  
**Estado de datos:** Anonimizados para protección de información sensible

---

## 📂 Estructura del Proyecto

📦 excel-to-mysql-migration/

├── 📄 README.md # Documentación principal (este archivo)

├── 📂 01-datos-origen/ # Datos originales

│ ├── informe-original-anonimizado.xlsx # Excel anonimizado

│ └── descripcion-datos.md # Descripción de columnas y estructura

├── 📂 02-analisis-diseno/ # Análisis y modelado

│ ├── analisis-estructura.md # Análisis del Excel original

│ ├── diagrama-er.png # Diagrama Entidad-Relación

│ └── normalizacion.md # Proceso de normalización aplicado

├── 📂 03-scripts-sql/ # Scripts de base de datos

│ ├── 01-create-database.sql # Creación de base de datos

│ ├── 02-create-tables.sql # Creación de tablas

│ ├── 03-insert-data.sql # Inserción de datos

│ └── 04-queries-ejemplo.sql # Consultas de ejemplo y reportes

├── 📂 04-documentacion/ # Documentación adicional

│ ├── guia-instalacion.md # Cómo reproducir el proyecto

│ └── lecciones-aprendidas.md # Aprendizajes del proceso

└── 📄 .gitignore # Archivos ignorados por Git

---

## 🛠️ Tecnologías Utilizadas

- **MySQL 8.0+** - Sistema de gestión de bases de datos
- **Microsoft Excel** - Origen de datos
- **Git & GitHub** - Control de versiones y documentación
- **Markdown** - Documentación técnica
- **Perplexity (AI Assistant)** – Asistente de inteligencia artificial para orientación en documentación, flujo de trabajo y dudas técnicas

---

## 🚀 Proceso de Migración

### 1️⃣ Análisis de Datos Origen
- Identificación de entidades y relaciones
- Detección de redundancias y dependencias
- Mapeo de tipos de datos

### 2️⃣ Diseño de Base de Datos
- Aplicación de normalización (1FN, 2FN, 3FN)
- Creación de diagrama Entidad-Relación
- Definición de claves primarias y foráneas

### 3️⃣ Implementación SQL
- Scripts de creación de base de datos
- Scripts de creación de tablas con constraints
- Scripts de inserción de datos

### 4️⃣ Validación y Consultas
- Consultas de ejemplo para reportes
- Validación de integridad referencial
- Comparación con datos originales

---

## 📊 Estado del Proyecto

- [x] Creación de repositorio y estructura
- [ ] Análisis de datos origen
- [ ] Diseño de base de datos
- [ ] Normalización
- [ ] Creación de scripts SQL
- [ ] Inserción de datos de prueba
- [ ] Consultas y reportes
- [ ] Documentación completa

---

## 💡 Aprendizajes Clave

_Esta sección se actualizará conforme avance el proyecto_

---

## 👤 Autor

**Ronald Maldonado**  
📧 [GitHub Profile](https://github.com/rmaldonado-builds)

---

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

---

## 🔗 Enlaces Relacionados

- [Documentación MySQL](https://dev.mysql.com/doc/)
- [Guía de Normalización de Bases de Datos](https://www.guru99.com/database-normalization.html)

---

**⭐ Si este proyecto te resulta útil, dale una estrella en GitHub**
