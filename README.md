# Planificación TFG - ASIR

```mermaid
gantt
    title Cronograma Proyecto Fin de Grado
    dateFormat  YYYY-MM-DD
    axisFormat  %d/%m

    section Fase 1: Planificación
    Elección del tema           :         des1, 2026-02-01, 3d
    Búsqueda bibliográfica      :         des2, after des1, 5d
    Redacción anteproyecto      :         des3, after des2, 5d

    section Fase 2: Ejecución
    Instalación Servidor        :         crit, 2026-02-15, 7d
    Configuración Servicios     :         crit, 2026-02-22, 10d
    Diseño Packet Tracer        :         2026-02-22, 10d
    
    section Fase 3: Documentación
    Redacción Memoria           :         2026-03-05, 20d
    Preparación Defensa         :         2026-03-25, 5d

    section Fase 4: Preparación de la Defensa
    Redacción del discurso de defensa (Script cronometrado) :c1, 2026-04-20, 10d
    Presentación PowerPoint                                 :c1, 2026-04-20, 10d
    Preparación y aseguramiento del entorno de DEMO en vivo :c2, 2026-04-20, 14d
    
    
    section HITO FINAL
    DÍA DE LA DEFENSA ANTE TRIBUNAL :milestone, 2026-05-21, 0d

