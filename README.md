# Proyecto ESP32 como Webserver con WebSockets y Render 3D de MPU6050 🌐🤖

Este proyecto consiste en utilizar un ESP32 como un servidor web que implementa WebSockets para transmitir los datos de una IMU MPU6050 (Acelerómetro y Giroscopio) a una página web. La página web incluirá un render 3D que mostrará la posición en tiempo real de la IMU.

## Características 🛠️

- **Servidor Web Integrado:** El ESP32 actúa como un servidor web que proporciona una interfaz para la visualización de datos de la IMU y control de la misma.

- **Comunicación por WebSockets:** Utiliza WebSockets para la transmisión de datos en tiempo real entre el ESP32 y la página web.

- **Render 3D en la Página Web:** La página web incluye un render 3D que muestra la posición de la IMU en tiempo real, proporcionando una representación visual intuitiva.

## Componentes Necesarios 📦

- ESP32 (con soporte para WiFi)
- Módulo MPU6050 (IMU Acelerómetro/Giroscopio)
- Conexión a Internet (WiFi)
- Un navegador web compatible con WebGL para visualizar la página web (Chrome, Firefox, etc.)

## Instrucciones de Uso 📝

1. **Conexión de Componentes:** Conecta el ESP32 y la IMU MPU6050 según las especificaciones del esquemático proporcionado en el código.

2. **Carga del Código:** Carga el código proporcionado en el ESP32 utilizando el IDE de Arduino o tu entorno de desarrollo preferido.

3. **Acceso a la Página Web:** Una vez cargado el código, accede a la dirección IP del ESP32 desde un navegador web compatible para ver la página web con el render 3D de la IMU.

## Ejemplo de Esquemático 📋

🎥[Video](https://www.youtube.com/watch?v=516be4dHADc)

## Contribuciones 🚀

¡Contribuciones son bienvenidas! Si tienes ideas para mejorar el proyecto, corregir errores o agregar nuevas características, no dudes en abrir un "issue" o enviar un "pull request".

## Créditos 🙌

Este proyecto fue creado por [Tu Nombre] y está inspirado en proyectos similares de la comunidad de IoT y desarrollo web.

## Licencia 📝

Este proyecto está bajo la licencia [MIT](LICENSE).
