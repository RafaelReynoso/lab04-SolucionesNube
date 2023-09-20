
# Laboratorio 04 - REYNOSO DAVILA

Este proyecto demuestra la implementación de tres rutas principales (inicio, clientes, productos) alojadas en Docker.

## Descripción del Proyecto

Para la realización de este laboratorio, se creó una máquina virtual en AWS EC2, aprovechando la capa gratuita disponible. La máquina virtual utilizada ejecuta Ubuntu como sistema operativo y se emplearon las tecnologías Node.js y Express para desarrollar este proyecto.

## Uso del Proyecto en Local

Para utilizar este proyecto en un entorno local, siga los siguientes pasos:

1. **Clonar el repositorio**:

    ```bash
    git clone https://github.com/RafaelReynoso/lab04-SolucionesNube.git
    ```

2. **Abrir la terminal y navegar hasta el directorio del proyecto**:

    ```bash
    cd lab04-SolucionesNube
    ```

3. **Instalar las dependencias utilizando npm**:

    ```bash
    npm install
    ```

4. **Iniciar la aplicación**:

    ```bash
    npm start
    ```

El proyecto proporciona las siguientes rutas en LOCAL:

1. [localhost:5000/](http://localhost:5000/)
2. [localhost:5000/productos](http://localhost:5000/productos)
3. [localhost:5000/clientes](http://localhost:5000/clientes)

## Uso del Proyecto con Docker
![image](https://github.com/Tecsupsoft/lab04-microservicios-RafaelReynoso/assets/67761441/60db772b-a8a2-40c9-9d91-edcf7e319af0)


También puede ejecutar este proyecto utilizando Docker. Siga estos pasos:

1. **Buscar mi usuario de DockerHub rafaelreynoso**:

    ```bash
    docker search rafaelreynoso
    ```

2. **Descargar el contenedor llamado "lab04" con la imagen "rafaelreynoso/lab04-reynoso"**:

    ```bash
    docker pull rafaelreynoso/lab04-reynoso
    ```

## Capturas de la aplicacion con AWS y Docker
![image](https://github.com/Tecsupsoft/lab04-microservicios-RafaelReynoso/assets/67761441/b3643386-ede6-42e5-8875-f5a66b695abd)
![image](https://github.com/Tecsupsoft/lab04-microservicios-RafaelReynoso/assets/67761441/c5e58c9a-b9fd-450e-a200-cabb73e0cc33)
![image](https://github.com/Tecsupsoft/lab04-microservicios-RafaelReynoso/assets/67761441/4c26d9d4-f14f-4cb7-9912-d62e9eb86aa0)

