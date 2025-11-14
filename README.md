# 🐔 **Chicken Suite – Propuesta de Proyecto Final**
Aplicación web modular para la gestión productiva, biológica y económica de granjas avícolas.  
Desarrollada en **Java**, **OpenXava 7.4**, **Maven**, **PostgreSQL embebida/SQLite** y **IntelliJ IDEA**.  
Color institucional sugerido: **#0099A8**.

---

<div align="center">

[![Java](https://img.shields.io/badge/Java-17+-0099A8?logo=openjdk&logoColor=white)](#)
[![OpenXava](https://img.shields.io/badge/OpenXava-7.4-0099A8.svg)](#)
[![Maven](https://img.shields.io/badge/Build-Maven-0099A8.svg)](#)
[![Status](https://img.shields.io/badge/Estado-En%20Desarrollo-c9d1d9.svg)](#)
[![UAM](https://img.shields.io/badge/UAM-Proyecto%20Académico-0099A8.svg)](#)

</div>

---

# 📌 **Tabla de Contenido**
- [📘 Información general del proyecto](#-información-general-del-proyecto)
- [🔎 Definición del problema](#-definición-del-problema)
- [🎯 Objetivos](#-objetivos)
- [📚 Alcance del sistema](#-alcance-del-sistema)
- [👥 Actores y usuarios](#-actores-y-usuarios)
- [🧩 Requerimientos del sistema](#-requerimientos-del-sistema)
- [🧱 Arquitectura general](#-arquitectura-general)
- [📦 Recursos necesarios](#-recursos-necesarios)
- [📅 Cronograma de desarrollo](#-cronograma-de-desarrollo)
- [👥 Equipo de trabajo](#-equipo-de-trabajo)
- [📝 Licencia](#-licencia)

---

# 📘 **Información general del proyecto**

| Campo | Descripción |
|-------|-------------|
| **Título del proyecto** | **Chicken Suite** |
| **Tipo de sistema** | Aplicación web modular desarrollada en **OpenXava**, ejecutable localmente **sin conexión a internet** |
| **Breve descripción** | Chicken Suite digitaliza la gestión diaria de granjas avícolas, permitiendo registrar lotes, especies, mortalidad, alimentación, costos y proyecciones económicas. Su enfoque es de *inteligencia productiva*, integrando datos biológicos y operativos para mejorar la eficiencia y la toma de decisiones. |

---

# 🔎 **Definición del problema**

## 🐣 Situación problemática
Las granjas avícolas pequeñas y medianas continúan llevando registros en cuadernos o documentos dispersos. Esto genera:
- Falta de integración entre datos productivos y financieros.  
- Errores en control de alimentación, limpieza y mortalidad.  
- Pérdida de trazabilidad del ciclo productivo.  
- Baja capacidad para estimar costos reales y rentabilidad.  

## 💡 Justificación
El sector avícola rural de Nicaragua necesita herramientas accesibles que no dependan de conexión a internet y permitan:
- Control confiable y estructurado del ciclo de producción.  
- Análisis económico por etapas.  
- Digitalización de procesos con bajo costo.  

**Chicken Suite** atiende esas necesidades con un sistema modular, local y adaptable.

---

# 🎯 **Objetivos**

## 🎯 Objetivo General
Desarrollar un sistema de escritorio que integre la gestión biológica y económica de granjas avícolas, permitiendo la proyección del ciclo completo desde incubación hasta comercialización.

## 🎯 Objetivos Específicos
- Diseñar una interfaz intuitiva para creación y monitoreo de lotes por especie.  
- Implementar un módulo de seguimiento diario: alimentación, vacunación, limpieza y mortalidad.  
- Desarrollar una línea de tiempo productiva por lote.  
- Integrar un sistema de proyección de costos e ingresos.  
- Permitir comparar escenarios productivos entre razas y especies.  

---

# 📚 **Alcance del sistema**

El sistema permitirá gestionar:
- Información de lotes avícolas.  
- Especies, razas, etapas, alimentación, mortalidad y rendimiento.  
- Proyecciones económicas por etapa y por ciclo.  
- Reportes visuales del crecimiento y alertas por cambio de etapa.

**Fuera de alcance:**
- Sistemas contables completos.  
- Sincronización en la nube.  
- Integración con plataformas externas.  

---

# 👥 **Actores y usuarios**

| Actor | Descripción / Rol |
|-------|--------------------|
| **Administrador** | Configura especies, razas, costos base y parámetros del sistema. |
| **Productor** | Registra la información diaria de los lotes. |
| **Analista** | Evalúa reportes productivos y financieros generados por el sistema. |

---

# 🧩 **Requerimientos del sistema**

## ✔ Requerimientos funcionales
- Registrar especies, razas y lotes.  
- Registrar alimentación, vacunación, limpieza y mortalidad.  
- Mostrar línea de tiempo del crecimiento por lote.  
- Generar reportes productivos y económicos.  
- Realizar proyecciones de costos e ingresos.  
- Comparar escenarios entre razas o especies.  

## ✔ Requerimientos no funcionales
- Interfaz moderna y responsiva (JavaFX o Swing).  
- Base de datos local (SQLite o PostgreSQL embebida).  
- Acceso seguro mediante usuario.  
- Rendimiento óptimo en hardware básico.  
- Independencia total de internet.  
- Modularidad escalable hacia móvil o IoT.  

---

Framework principal: **OpenXava 7.4**  
Lenguaje: **Java 17+**  
Empaquetado: **Maven**  

---

# 📦 **Recursos necesarios**

- **Lenguaje:** Java (JDK 17 o superior)  
- **Framework:** OpenXava 7.4  
- **IDE:** IntelliJ IDEA / Eclipse  
- **Base de datos:** PostgreSQL embebida o SQLite  
- **Control de versiones:** GitHub  
- **Librerías:** Lombok, Hibernate, JavaFX, JPA  
- **UI:** CSS personalizado (paleta #0099A8)  

---

# 📅 **Cronograma de desarrollo**

| Etapa | Actividad | Semana |
|--------|-----------|--------|
| **Análisis** | Requerimientos y modelo de clases | 11 |
| **Diseño** | Entidades y vistas en OpenXava | 12 |
| **Desarrollo** | Módulos CRUD | 13–14 |
| **Pruebas** | Validación y corrección | 15 |
| **Presentación** | Exposición y documentación | 16 |

---

# 👥 **Equipo de trabajo**

| CIF | Integrante | Rol |
|------|------------|------|
| 24010195 | Diedereich Alexander Alemán Martínez | Desarrollador |
| 23020360 | Diego Francisco Mora Castillo | Coordinador |
| 24010528 | Elias Adrian Marín Cruz | Analista |
| 24010572 | David Alejandro Espinoza Largaesada | Soporte |

---

# 📝 **Licencia**
Proyecto académico para la asignatura **Metodología y Programación Orientada a Objetos I – UAM**.  
Uso educativo — 2025.

---

<div align="center">
Hecho con ❤️ en Nicaragua · Color institucional: <strong>#0099A8</strong>
</div>
