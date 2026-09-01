```mermaid

flowchart TD
A([INICIO]) --> B[/Registrar/]
    B --> C{¿Datos completos?}
    C -- Sí --> D{¿El correo exite?}
    D -- Sí --> E[Advertencia]
    D -- No --> H[Registro]
    C -- No --> F[Mostrar datos faltantes]
    H --> G
    F --> G
    E --> G([FIN])
    ```