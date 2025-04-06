# LegerBot
\* Primera Iteracion
El proyecto busca automatizar la ejecución y automatización del test de Léger, eliminando la intervencion manual e intercambiando las alertas sonoras a una alerta visual (Luces). A traves del uso de MCU se sincronizara el control centrar con un par de tripodes con luces y un MCU's, se tomara los datos de los participantes en tiempo real para generar las métricas de estos.
La motivación detrás de este proyecto radica en la necesidad de modernizar y optimizar la aplicación del Test de Léger, eliminando errores humanos y mejorando la precisión en la medición del rendimiento físico.
*\Segunda Iteracion

LegerBot es un sistema de torres luminosas inalámbricas diseñado para la automatización del test de Leger, intercambiando las alertas sonoras por alertas visuales. El sistema consta de dos torres autónomas equipadas con LEDs de alta intensidad, baterías recargables y módulos de comunicación inalámbrica. El control del sistema se realiza a través de una aplicación móvil instalada en un teléfono inteligente, el cual actuará como un punto de acceso Wi-Fi (Hotspot) al que se conectarán ambas torres. La aplicación de celular tendrá la opción de iniciar o detener el Test de Leger

Procesamiento de Datos:

El microcontrolador de cada torre debe procesar los comandos recibidos vía Wi-Fi desde la aplicación móvil para controlar los LEDs.

El sistema debe ser capaz de ejecutar la secuencia del test de Leger

Comunicación:

Las torres deben comunicarse de forma inalámbrica vía Wi-Fi, conectándose al Hotspot generado por el teléfono inteligente.

Control:

La aplicación móvil debe permitir el inicio y la detención de la secuencia.

Gestión de Energía:

El sistema debe funcionar con baterías recargables en cada torre.

Interfaz de Usuario (Aplicación Móvil):

La aplicación móvil debe tener una interfaz de usuario intuitiva y fácil de usar para controlar las torres.

Seguridad:

La seguridad de la comunicación estará principalmente gestionada por la seguridad del Hotspot Wi-Fi del teléfono.

Tiempos de Respuesta:

El sistema debe responder a los comandos de control desde la aplicación móvil con baja latencia.

Las secuencias de iluminación deben ejecutarse con precisión temporal.

Cumplimiento de Estándares:

Asegurarse de que el uso del módulo Wi-Fi en las torres cumpla con las regulaciones locales de espectro radioeléctrico en Colombia.

Análisis y Consideraciones Adicionales Específicas para esta Arquitectura:

Dependencia del Celular: El sistema depende completamente del teléfono inteligente para la comunicación. La disponibilidad y batería del celular se vuelven críticas.

Rango del Hotspot: El rango de comunicación estará limitado por la potencia del Hotspot Wi-Fi del teléfono. Es importante considerar la distancia máxima entre las torres y el teléfono durante el test de Leger.

Desarrollo de la Aplicación Móvil: El desarrollo de una aplicación móvil robusta y fácil de usar se convierte en un componente central del proyecto.

Consideraciones de Conexión: La aplicación móvil deberá gestionar la conexión y desconexión de las torres al Hotspot, así como posibles interrupciones en la señal.




------------------------------
No requisitos funcionales
------------------------------
El escenario es una pista de atletismo o una cancha, se puede realizar en cualquier espacio que cuente con una longitud de 20 metros.
------------------------------
Se piensa reducir el precio total, quitando los MCU los cuales se tomarían prestados y las baterías las cuales en estos momentos estamos buscando usarlas prestadas. También se tiene pensado cambiar las balizas por tiras de led's. Esta lista de precios no es definitiva, se tiene pensado reducir costos a medida que avanza el proyecto.
