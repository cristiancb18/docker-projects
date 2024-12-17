# Conversor de Monedas Dockerizado

Este es un proyecto de conversor de monedas que utiliza Docker para contenerizar la aplicación. Esta proporciona una interfaz de usuario simple para convertir una moneda a otra, utilizando una API externa para obtener las tasas de cambio en tiempo real.

La imagen de Docker está disponible en Docker Hub, lo que permite ejecutar la aplicación fácilmente sin necesidad de construir la imagen desde cero.

## Tecnologías Utilizadas

- **Docker**: Para la creación y ejecución del contenedor.
- **Node.js**: Para el servidor backend que maneja las solicitudes y sirve los archivos estáticos.
- **HTML**: Para la interfaz de usuario del frontend.
- **API Externa**: Utiliza una API para obtener tasas de cambio actuales de diferentes monedas.

## Requisitos

Para ejecutar este proyecto en tu máquina local, necesitarás tener instalado lo siguiente:

- **Docker**: Para descargar y ejecutar la imagen del contenedor.
- **Git** (opcional): Para clonar el repositorio.

## Cómo Ejecutar el Proyecto desde Docker Hub

1. **Ejecutar el contenedor Docker desde Docker Hub**:

   Usamos la imagen desde Docker Hub con el siguiente comando:

    ```bash
    docker run -p 8080:8080 crisbeltran97/conversor-monedas
    ```

   Esto descargará la imagen `crisbeltran97/conversor-monedas` de Docker Hub y expondrá la aplicación en `http://localhost:8080`.

2. **Acceder al Proyecto**:

    Abre tu navegador y ve a `http://localhost:8080` para usar el conversor de monedas.

## Cómo Contribuir

Si deseas contribuir a este proyecto, sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una rama con tu feature o arreglo de bug: `git checkout -b mi-feature`.
3. Haz commit de tus cambios: `git commit -m 'Agregado mi feature'`.
4. Haz push a tu rama: `git push origin mi-feature`.
5. Crea un pull request describiendo los cambios realizados.

## Licencia

Este proyecto está licenciado bajo la **Licencia MIT**.

## Contacto

Si tienes alguna pregunta o sugerencia, no dudes en contactarme a través de [tu correo electrónico] o en GitHub.
