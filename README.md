# EFI Flask + Docker realizado por Mariano Leonel Ison y Mateo Roble

## Requisitos Previos

Asegúrate de tener instalados los siguientes elementos antes de comenzar:

- [Docker](https://www.docker.com/)

## Instalación

1. Clona este repositorio:

    ```bash
    git clone git@github.com:MateoRoble/EFI_DOCKER.git
    ```

2. Copia el archivo `.env.example` y renómbralo a `.env`. Luego, configura las variables de entorno según tus necesidades.

    ```bash
    cp .env.sample .env
    ```

3. Construye y levanta los contenedores de Docker:

    ```bash
    docker-compose up --build
    ```

4. La aplicación debería estar disponible en [http://localhost:5005](http://localhost:5005).

## Uso

Puedes interactuar con la aplicación realizando consultas a través de Thunder Client, Postman o cualquier otra herramienta de prueba de API que prefieras.
