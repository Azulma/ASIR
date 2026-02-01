# Planificación TFG - ASIR

```mermaid
gantt
    title Cronograma Proyecto Fin de Grado
    dateFormat  YYYY-MM-DD
    axisFormat  %d/%m

    section Fase 1: Investigación
    Elección del tema           :done,    des1, 2026-02-01, 3d
    Búsqueda bibliográfica      :active,  des2, after des1, 5d
    Redacción anteproyecto      :         des3, after des2, 5d

    section Fase 2: Ejecución
    Instalación Servidor        :         crit, 2026-02-15, 7d
    Configuración Servicios     :         2026-02-22, 10d
    
    section Fase 3: Documentación
    Redacción Memoria           :         2026-03-05, 20d
    Preparación Defensa         :         2026-03-25, 5d
