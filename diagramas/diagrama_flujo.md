flowchart TD
A([INICIO]) --> B[/Capturar datos del asistente/]
    B --> C{¿Datos completos?}
    C -- Sí --> D[Registro asistente]
    D --> E[/Mostrar confirmación/]
    C -- No --> F[/Mostrar datos faltantes/]
    F --> E
    E --> G([FIN])
    F --> E 