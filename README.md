# LegerBot
\*
El proyecto busca automatizar la ejecución y automatización del test de Léger, eliminando la intervencion manual e intercambiando las alertas sonoras a una alerta visual (Luces). A traves del uso de MCU se sincronizara el control centrar con un par de tripodes con luces y un MCU's, se tomara los datos de los participantes en tiempo real para generar las métricas de estos.
La motivación detrás de este proyecto radica en la necesidad de modernizar y optimizar la aplicación del Test de Léger, eliminando errores humanos y mejorando la precisión en la medición del rendimiento físico.
*\
LegerBot es un sistema de torres luminosas inalámbricas diseñado para la automatización del test de Leger, intercambiando las alertas sonoras por alertas visuales. El sistema consta de dos torres autónomas equipadas con LEDs de alta intensidad, baterías recargables y módulos de comunicación inalámbrica. El control del sistema se puede realizar de dos maneras:

Opción 1: A través de un sistema de control centralizado (por ejemplo, una computadora o un controlador dedicado) que se comunica con ambas torres vía Wi-Fi.

Opción 2: Directamente desde una de las torres, que actúa como unidad maestra y se comunica con la segunda torre también vía Wi-Fi.

El sistema permite iniciar y detener secuencias de iluminación predefinidas (secuencia del test de Leger), ajustar la intensidad y el color de los LEDs, y recibir retroalimentación sobre el estado de las torres (nivel de batería, estado de la conexión, etc.).

Diagrama de Bloques:

Torre Luminosa:

Módulo de LEDs (RGB o monocromáticos de alta intensidad).

Microcontrolador (para control de LEDs, comunicación y gestión de energía).

Módulo Wi-Fi (para comunicación inalámbrica).

Batería recargable y circuito de gestión de energía.

Sensor de nivel de batería.

Estructura de soporte (trípode o mástil).

Sistema de Control Central (Opción 1):

Computadora o controlador dedicado.

Interfaz de usuario (software o panel de control).

Módulo Wi-Fi (para comunicación con las torres).

Torre Maestra (Opción 2):

Los mismos componentes que la "Torre Luminosa"

Interfaz de usuario (botones, pantalla o similar) para control local.
------------------------------
Procesamiento de Datos:

El microcontrolador de cada torre debe procesar los comandos recibidos vía Wi-Fi para controlar los LEDs.

El sistema debe ser capaz de ejecutar secuencias de iluminación predefinidas almacenadas en la memoria del microcontrolador.

El sistema debe poder transmitir datos de telemetría (nivel de batería, estado de la conexión) al sistema de control central o a la torre maestra.

Comunicación:

Las torres deben comunicarse de forma inalámbrica vía Wi-Fi con el sistema de control central o entre sí.

El protocolo de comunicación debe ser confiable y con baja latencia.

El sistema debe permitir la configuración de la red Wi-Fi (SSID, contraseña, etc.).

Control:

El sistema debe permitir el inicio y la detención de secuencias de iluminación predefinidas.

El sistema debe proporcionar retroalimentación sobre el estado de las torres (estado de la conexión, nivel de batería, etc.).

Gestión de Energía:

El sistema debe funcionar con baterías recargables.

El sistema debe proporcionar información sobre el nivel de batería.

Interfaz de Usuario:

El sistema de control central (Opción 1) debe tener una interfaz de usuario intuitiva para controlar las torres.

La torre maestra (Opción 2) debe tener una interfaz de usuario local (botones, pantalla, etc.) para el control básico.

Seguridad:

El sistema debe implementar medidas de seguridad para proteger la comunicación inalámbrica (cifrado, autenticación).

Tiempos de Respuesta:

El sistema debe responder a los comandos de control con baja latencia.

Las secuencias de iluminación deben ejecutarse con precisión temporal.
------------------------------
No requisitos funcionales
------------------------------
El escenario es una pista de atletismo o una cancha, se puede realizar en cualquier espacio que cuente con una longitud de 20 metros.
------------------------------
