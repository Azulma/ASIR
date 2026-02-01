# Planificación TFG - ASIR

```mermaid
gantt
    title Cronograma Proyecto Fin de Grado
    dateFormat  YYYY-MM-DD
    axisFormat  %d/%m

    section Fase 1: Planificación
    Elección del tema           :         F1a, 2026-01-27, 3d
    Búsqueda bibliográfica      :         F1b, after F1a, 5d
    Redacción memoria           :         F1c, after F1b, 5d

    section Fase 2: Ejecución
    Instalación Servidor        :         crit, 2026-02-01, 8d
    Diseño Packet Tracer        :               2026-02-09, 5d
    Configuración Servicios     :         crit, 2026-02-14, 15d

    
    section Fase 3: Documentación
    Redacción Memoria           :         2026-03-05, 20d
    Preparación Defensa         :         2026-03-25, 5d

    section Fase 4: Preparación de la Defensa
    Redacción del discurso de defensa (Script cronometrado) :c1, 2026-04-20, 10d
    Presentación PowerPoint                                 :c1, 2026-04-20, 10d
    Preparación y aseguramiento del entorno de DEMO en vivo :c2, 2026-04-20, 14d
    
    
    section ENTREGAS PROYECTO
    1º Entrega 1     :milestone, 2026-03-01, 0d
    DEFENSA PROYECTO :milestone, 2026-05-21, 0d

