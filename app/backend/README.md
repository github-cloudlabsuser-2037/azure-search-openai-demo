# Azure Search OpenAI Demo - Backend

## Descripción

Este proyecto es una demostración de cómo integrar Azure Search con OpenAI en una aplicación backend. Proporciona una API que permite realizar búsquedas avanzadas utilizando el poder de OpenAI y la capacidad de búsqueda de Azure.

## Requisitos

- Node.js
- Azure Subscription
- OpenAI API Key

## Instalación

1. Clona el repositorio:
    ```bash
    git clone https://github.com/tu-usuario/azure-search-openai-demo.git
    ```
2. Navega al directorio del backend:
    ```bash
    cd azure-search-openai-demo/app/backend
    ```
3. Instala las dependencias:
    ```bash
    npm install
    ```

## Configuración

1. Crea un archivo `.env` en el directorio `backend` con las siguientes variables:
    ```plaintext
    AZURE_SEARCH_API_KEY=tu-azure-search-api-key
    OPENAI_API_KEY=tu-openai-api-key
    ```

## Uso

1. Inicia el servidor:
    ```bash
    npm start
    ```
2. La API estará disponible en `http://localhost:3000`.

## Endpoints

- `GET /search`: Realiza una búsqueda utilizando Azure Search y OpenAI.
    - Parámetros de consulta:
        - `query`: La consulta de búsqueda.

## Contribuciones

Las contribuciones son bienvenidas. Por favor, abre un issue o un pull request para discutir cualquier cambio.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo `LICENSE` para más detalles.
```

```markdown