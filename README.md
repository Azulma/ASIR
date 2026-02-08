# 🎓 Proyecto TFG - Administración de Sistemas (ASIR)

![Estado](https://img.shields.io/badge/Estado-En_Desarrollo-blue)
![Curso](https://img.shields.io/badge/Curso-2025%2F2026-lightgrey)
![Fecha Fin](https://img.shields.io/badge/Entrega_Final-07_Mayo-critical)
[![Ver Dashboard en Vivo](https://img.shields.io/badge/⚡_Ver-Dashboard_Tiempo_Real-27ae60?style=for-the-badge)](dashboard.html)

Este documento detalla la planificación temporal estricta para el desarrollo del Trabajo de Fin de Grado, estructurado en 4 fases de entrega y la defensa final.

> **Nota:** Para ver los cálculos de días restantes en tiempo real, abre el archivo `dashboard.html` en tu navegador o [haz clic aquí](dashboard.html) si estás viendo este repositorio en local. Si estás en GitHub, necesitas activar **GitHub Pages** para verlo online.

---

## 📅 Cronograma Visual

```mermaid
%%{init: { 
  'gantt': { 'barHeight': 45, 'fontSize': 14, 'fontFamily': 'Segoe UI, Roboto, Helvetica, sans-serif' }, 
  'theme': 'base', 
  'themeVariables': { 
    'background': '#ffffff',
    'primaryColor': '#2c3e50', 
    'secondaryColor': '#b0bec5', 
    'tertiaryColor': '#cfd8dc', 
    'primaryBorderColor': '#1a252f', 
    'primaryTextColor': '#ffffff', 
    'secondaryTextColor': '#000000', 
    'tertiaryTextColor': '#000000', 
    'lineColor': '#2c3e50', 
    'milestoneBackground': '#f1c40f', 
    'milestoneBorderColor': '#d35400', 
    'criticalColor': '#c0392b', 
    'criticalBorderColor': '#8e44ad', 
    'criticalTextColor': '#ffffff',
    'gridColor': '#ffffff' 
  } 
}}%%
gantt
    title Roadmap TFG 2026
    dateFormat  YYYY-MM-DD
    axisFormat  %d/%m
    todayMarker off

    section Fase 1: Planificacion (Entrega 1)
    Eleccion del tema y Bibliografia :done,    T1, 2026-02-15, 2026-02-25
    Redaccion Entrega 1              :active,  T2, 2026-02-26, 2026-03-01
    ENTREGA PARCIAL 1                :milestone, M1, 2026-03-02, 0d

    section Fase 2: Ejecucion (Entrega 2)
    Instalacion y Config. Basica     :crit,    T3, 2026-03-03, 2026-03-17
    Diseno Red y Pruebas Iniciales   :         T4, 2026-03-18, 2026-04-02
    Redaccion Entrega 2              :         T5, 2026-04-03, 2026-04-06
    ENTREGA PARCIAL 2                :milestone, M2, 2026-04-07, 0d

    section Fase 3: Avance (Entrega 3)
    Configuracion Avanzada Servicios :crit,    T6, 2026-04-08, 2026-04-20
    Pruebas de Seguridad y Ajustes   :         T7, 2026-04-21, 2026-04-29
    Redaccion Entrega 3              :         T8, 2026-04-30, 2026-05-03
    ENTREGA PARCIAL 3                :milestone, M3, 2026-05-04, 0d

    section Fase 4: Finalizacion
    Revision Final Memoria           :crit,    T9, 2026-05-05, 2026-05-06
    Creacion Presentacion            :         T10, 2026-05-05, 2026-05-06
    ENTREGA FINAL (Memoria+Pres.)    :milestone, M4, 2026-05-07, 0d

    section Defensa
    Preparacion Demo y Ensayo        :         T11, 2026-05-08, 2026-05-25
    DEFENSA TFG (Estimada)           :milestone, M5, 2026-06-10, 0d
```

---

## 📋 Detalle de Tareas

| Fase | Tarea | Periodo | Duración | Días hasta Entrega* |
| :--- | :--- | :--- | :--- | :---: |
| **Fase 1** | 🔍 Elección del tema y Bibliografía | 15 Feb - 20 Feb | 6 días | - |
| | 📅 Planificación Detallada | 21 Feb - 25 Feb | 5 días | - |
| | ✍️ **Redacción Entrega 1** | **26 Feb - 01 Mar** | **4 días** | 3 Semanas |
| | 🏁 **HITO: Entrega Parcial 1** | **02 Mar** | | **22 días** |
| **Fase 2** | 🖥️ Instalación Servidor Base | 03 Mar - 15 Mar | 13 días | - |
| | 🌐 Diseño Red y Config. Básica | 16 Mar - 02 Abr | 18 días | - |
| | ✍️ **Redacción Entrega 2** | **03 Abr - 06 Abr** | **4 días** | ~2 Meses |
| | 🏁 **HITO: Entrega Parcial 2** | **07 Abr** | | **58 días** |
| **Fase 3** | ⚙️ Config. Avanzada Servicios | 08 Abr - 22 Abr | 15 días | - |
| | 🔒 Pruebas de Seguridad y Ajustes | 23 Abr - 29 Abr | 7 días | - |
| | ✍️ **Redacción Entrega 3** | **30 Abr - 03 May** | **4 días** | ~3 Meses |
| | 🏁 **HITO: Entrega Parcial 3** | **04 May** | | **85 días** |
| **Fase 4** | 📖 **Revisión Final Memoria** | **05 May - 06 May** | **2 días** | - |
| | 🏆 **HITO: Entrega Final Memoria** | **07 May** | | **88 días** |
| **Defensa** | 📢 Preparación Presentación y Guion | 08 May - 15 May | 8 días | - |
| | 🎭 Ensayo y Preparación Demo | 16 May - 25 May | 10 días | - |
