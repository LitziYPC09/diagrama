## 3. Flujo de Funcionamiento

```mermaid
graph TD
    A[Usuario abre la app] --> B[Activity Ingreso de Preferencias]
    B --> C[Sistema analiza la información]
    C --> D[Consulta la API de Fake Store]
    D --> E[Se obtiene la recomendación del producto]
    E --> F[Activity Resultados/Recomendación]
    F --> G[Activity Detalle del Producto (opcional)]
