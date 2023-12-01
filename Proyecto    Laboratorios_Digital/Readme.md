Propuesta de Proyecto: Espejo Lateral Mecanizado con Sistema de Ángulo Automático para Carros utilizando FPGA

1. Introducción:
En la conducción de vehículos, la visibilidad es esencial para garantizar la seguridad del conductor. Uno de los elementos clave para una buena visión es el espejo lateral del automóvil. Este proyecto propone el diseño e implementación de un espejo lateral mecanizado que ajusta automáticamente su ángulo en función de la proximidad de objetos cercanos al vehículo. Esto se logrará mediante el uso de un sensor de ultrasonido y un servomotor, controlados por una FPGA (Field-Programmable Gate Array).

2. Objetivo:
Desarrollar un sistema innovador que mejore la visibilidad del conductor al ajustar automáticamente el ángulo del espejo lateral en tiempo real, utilizando un sensor de ultrasonido para detectar la presencia de objetos cercanos.

3. Componentes del Sistema:
El proyecto constará de los siguientes elementos clave:

   - Sensor de Ultrasonido: Para medir la distancia entre el vehículo y los objetos cercanos.
   
   - Servomotor: Para controlar el ángulo del espejo lateral.
   
   - FPGA: Para procesar la información del sensor de ultrasonido y controlar el servomotor.

4. Funcionamiento:
   - El sensor de ultrasonido realizará mediciones de distancia en tiempo real.
   - La FPGA procesará la información del sensor y determinará la proximidad de objetos cercanos.
   - Si no se detectan objetos cercanos, la FPGA enviará una señal al servomotor para abrir el ángulo del espejo lateral, mejorando la visión periférica.
   - En caso de detectar objetos cercanos, la FPGA ajustará automáticamente el espejo lateral para obtener una mejor visualización de la situación.

5. Beneficios:
   - Mejora de la seguridad al proporcionar una visión óptima del entorno del vehículo.
   - Reducción de puntos ciegos al ajustar el ángulo del espejo de manera dinámica.
   - Integración eficiente de hardware mediante el uso de una FPGA para el procesamiento en tiempo real.

6. Metodología:
   - Diseño del circuito electrónico para la conexión del sensor de ultrasonido, el servomotor y la FPGA.
   - Desarrollo del código en hardware description language (HDL) para la FPGA.
   - Integración y pruebas del sistema en un entorno de laboratorio simulando diversas situaciones de conducción.

7. Resultados Esperados:
   - Un prototipo funcional de espejo lateral mecanizado con ángulo automático.
   - Documentación técnica detallada del diseño y la implementación.
   - Análisis de rendimiento y eficacia del sistema.

8. Conclusiones:
Este proyecto proporcionará una solución innovadora y efectiva para mejorar la seguridad en la conducción al optimizar la visibilidad a través de la automatización del ángulo del espejo lateral. La implementación en una FPGA permitirá un procesamiento eficiente y en tiempo real de los datos del sensor de ultrasonido, brindando una solución práctica y escalable.

<image src="Proyectos Laboratorios_Digital/sim/0000.jpg" alt="simulacion" width="400px">
