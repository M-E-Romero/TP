```mermaid
graph TD
    %% Definición de elementos limpios sin bordes ni fondos
    R["PO03 - Proyecto Final/"]
    C1["⚙️ CONFIGURACIÓN Y ARRANQUE"]
    F1["app.py"]
    F2["config.py"]
    F3["requirements.txt"]
    F4["seed.py"]
    F5["README.md"]
    F6[".gitignore"]

    %% Conexiones con estilo de árbol usando texto intermedio
    R --- L1["│"]
    L1 --- L2["├──"]
    L2 --> C1
    
    C1 --- L3["│"]
    L3 --- L4["├──"] --> F1
    L3 --- L5["├──"] --> F2
    L3 --- L6["├──"] --> F3
    L3 --- L7["├──"] --> F4
    L3 --- L8["├──"] --> F5
    L3 --- L9["└──"] --> F6

    %% Quitar cajas y bordes molestos para que parezca texto puro de directorio
    style R fill:none,stroke:none
    style C1 fill:none,stroke:none
    style F1 fill:none,stroke:none
    style F2 fill:none,stroke:none
    style F3 fill:none,stroke:none
    style F4 fill:none,stroke:none
    style F5 fill:none,stroke:none
    style F6 fill:none,stroke:none
    style L1 fill:none,stroke:none
    style L2 fill:none,stroke:none
    style L3 fill:none,stroke:none
    style L4 fill:none,stroke:none
    style L5 fill:none,stroke:none
    style L6 fill:none,stroke:none
    style L7 fill:none,stroke:none
    style L8 fill:none,stroke:none
    style L9 fill:none,stroke:none
```
