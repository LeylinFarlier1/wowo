# Tech Stack del Proyecto

Este documento describe las tecnologías principales utilizadas en el "Advanced Financial Intelligence Dashboard" y las razones de su elección.

### Backend

-   **Lenguaje: Python**
    -   *Razón:* Ecosistema maduro y robusto para ciencia de datos, desarrollo web y scripting. Las librerías como `pandas`, `yfinance` y `fredapi` son fundamentales para el proyecto.
-   **Framework: Django**
    -   *Razón:* Framework "baterías incluidas" que proporciona una estructura sólida (ORM, admin, seguridad) para un desarrollo rápido y seguro. Su arquitectura modular es perfecta para nuestro plan.
-   **API: Django REST Framework (DRF)**
    -   *Razón:* El estándar de oro para construir APIs RESTful en Django. Ofrece una enorme flexibilidad y acelera el desarrollo de endpoints.

### Base de Datos

-   **Sistema: PostgreSQL**
    -   *Razón:* Elegido por su robustez, fiabilidad y su potente manejo de datos relacionales. Es el estándar de facto para aplicaciones Django complejas y tiene excelentes capacidades para manejar datos de series temporales.

### Infraestructura y DevOps

-   **Control de Versiones: Git / GitHub**
    -   *Razón:* Estándar de la industria para el control de versiones y la colaboración. GitHub nos proporciona repositorio, seguimiento de issues y CI/CD en un solo lugar.
-   **Contenerización: Docker / Docker Compose**
    -   *Razón:* Garantiza la paridad entre los entornos de desarrollo, pruebas y producción. Simplifica la configuración inicial para nuevos desarrolladores y facilita el despliegue.
-   **CI/CD: GitHub Actions**
    -   *Razón:* Integración nativa y fluida con nuestro repositorio en GitHub para automatizar pruebas, linters y futuros despliegues.

### Frontend (Planificado)

-   **Framework CSS: Bootstrap / Tailwind CSS**
    -   *Razón:* Frameworks modernos que permiten construir interfaces de usuario responsivas y atractivas de manera eficiente.
-   **Librerías de Gráficos: Plotly.js / Chart.js**
    -   *Razón:* Librerías de JavaScript potentes y flexibles para crear las visualizaciones interactivas que son el corazón de este dashboard.