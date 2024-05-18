# BRAZO_ROBOTICO
# Diseño y ensamble de un brazo robótico articulado controlado por Arduino

## Descripción

Este proyecto consiste en el diseño y construcción de un brazo robótico articulado controlado mediante una placa Arduino. El objetivo es crear un sistema robótico que pueda realizar movimientos precisos y repetitivos, ideal para tareas como la manipulación de objetos, soldadura, ensamblaje y otras aplicaciones industriales.

## Características

- **Controlador:** Arduino Uno
- **Grados de libertad:** 6 (base rotativa, hombro, codo, muñeca rotativa, muñeca flexión/extensión, pinza)
- **Componentes principales:** Servomotores, estructura de aluminio, fuente de alimentación
- **Software:** IDE de Arduino, bibliotecas específicas para el control de servomotores
- **Interfaz de usuario:** Control manual mediante botones o control remoto, con posibilidad de programar secuencias de movimientos.

## Instalación

### Requisitos

- **Hardware:**
  - Arduino Uno
  - Servomotores (x6)
  - Fuente de alimentación adecuada para los servomotores
  - Componentes estructurales (perfiles de aluminio, tornillos, etc.)
  - Módulo de control remoto (opcional)

- **Software:**
  - [IDE de Arduino](https://www.arduino.cc/en/Main/Software)
  - Biblioteca Servo de Arduino (incluida en el IDE de Arduino)

### Pasos de instalación

1. **Ensamblaje del hardware:**
   - Siguiendo las instrucciones del diseño, montar la estructura del brazo robótico.
   - Conectar los servomotores a las articulaciones correspondientes.
   - Conectar los servomotores a la placa Arduino siguiendo el esquema de conexiones.

2. **Configuración del software:**
   - Descargar e instalar el IDE de Arduino.
   - Descargar el código fuente del repositorio y abrirlo en el IDE de Arduino.
   - Cargar el código en la placa Arduino.

3. **Prueba de funcionamiento:**
   - Conectar la fuente de alimentación.
   - Ejecutar pruebas básicas de movimiento para asegurar que todos los servomotores funcionen correctamente.
   - Ajustar el código según sea necesario para mejorar la precisión y respuesta del brazo.

## Uso

Una vez que el brazo robótico está ensamblado y el código cargado, puedes controlarlo de las siguientes maneras:

- **Control manual:** Utilizar los botones conectados al Arduino para mover las diferentes articulaciones del brazo.
- **Secuencias programadas:** Editar el código para incluir secuencias de movimientos predefinidas que el brazo ejecutará automáticamente.
- **Control remoto (opcional):** Utilizar un módulo de control remoto para enviar comandos al Arduino y controlar el brazo a distancia.


## Licencia

Este proyecto está licenciado bajo la Licencia MIT. Para más detalles, consulta el archivo [LICENSE](LICENSE).

## Contacto

Para cualquier consulta o sugerencia, puedes contactarme en [brayanstevenmoreno@uts.edu.co](mailto:brayanstevenmoreno@uts.edu.co).
