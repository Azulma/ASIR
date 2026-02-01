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


    section Fase 4: Simulación Packet Tracer (Diseño de Red)
    Análisis de la topología Docker actual para replicación :a1, 2026-02-12, 5d
    Diseño topológico en PT (Routers Central/Sucursal, Switches, Nube) :a2, after a1, 7d
    Configuración de Enrutamiento Base (IPs, rutas estáticas/RIP) :a3, after a2, 5d
    Simulación de Túnel VPN (Site-to-Site IPsec/GRE) :a4, after a3, 7d
    Pruebas de conectividad y captura de esquemas para PPT :crit, a5, after a4, 5d

    section Fase 5: Creación Presentación (PowerPoint)
    Estructuración del guion y narrativa (Storytelling) :b1, 2026-03-10, 10d
    Desarrollo de contenido textual y mensajes clave :b2, after b1, 12d
    Diseño visual de diapositivas (Plantilla y estilo corporativo) :b3, after b2, 10d
    Integración de diagramas (PT) y evidencias reales (Docker/Capturas) :b4, after a5 b3, 7d
    Revisión con tutor y refinamiento final del PPT :b5, after b4, 7d

    section Fase 6: Preparación de la Defensa
    Redacción del discurso de defensa (Script cronometrado) :c1, after b4, 10d
    Preparación y aseguramiento del entorno de DEMO en vivo :c2, 2026-04-20, 14d
    Simulacro de defensa 1 (Control de tiempos) :c3, after c1 c2, 3d
    Preparación del turno de preguntas (Q&A) y anexos técnicos :c4, after c3, 7d
    Simulacros finales intensivos y ajustes de oratoria :crit, c5, after c4, 10d
    
    section HITO FINAL
    DÍA DE LA DEFENSA ANTE TRIBUNAL :milestone, 2026-05-21, 0d

    'sectionBkgColor': '#ecf0f1',   // <-- Gris clarito
    'sectionBkgColor2': '#bdc3c7',  // <-- Gris un poco más oscuro
