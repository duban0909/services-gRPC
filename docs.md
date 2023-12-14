# Prueba de concepto sobre servicios GRPC

## Introducción

gRPC es un sistema de comunicación de código abierto desarrollado por Google que facilita la comunicación eficiente y confiable entre servicios distribuidos. Utiliza el protocolo HTTP/2 para la transmisión de datos de forma rápida y con baja latencia, permitiendo la comunicación entre diferentes plataformas y lenguajes de programación mediante la definición de servicios y mensajes mediante el uso de Protocol Buffers (protobufs). Esta tecnología se utiliza ampliamente en el desarrollo de aplicaciones distribuidas, microservicios y sistemas modernos de alto rendimiento.

## Ventajas

gRPC ofrece diversas ventajas, entre las que se incluyen una comunicación eficiente gracias al uso del protocolo HTTP/2, la capacidad de definir interfaces de manera clara y fácil mediante Protocol Buffers, soporte para varios lenguajes de programación, generación automática de código, manejo de errores robusto, y la posibilidad de realizar streaming bidireccional de datos, lo que lo convierte en una herramienta potente y versátil para el desarrollo de sistemas distribuidos de alto rendimiento.

## Desventajas

Aunque gRPC ofrece numerosas ventajas, algunas limitaciones incluyen una curva de aprendizaje inicial debido a su complejidad, lo que puede requerir tiempo adicional para comprender completamente su funcionamiento. Además, al utilizar HTTP/2, puede presentar dificultades de depuración debido a la opacidad de los mensajes en comparación con otras tecnologías. Asimismo, el soporte puede ser limitado para algunos lenguajes de programación en comparación con otros protocolos más establecidos, lo que puede representar un desafío para integraciones específicas en ciertos entornos. Sin embargo, con la continua evolución y el soporte de la comunidad, estas limitaciones tienden a ser abordadas progresivamente.

## Conclusión

En resumen, gRPC es una tecnología poderosa que ofrece una comunicación eficiente y confiable entre servicios distribuidos utilizando HTTP/2 y Protocol Buffers. Aunque tiene desafíos como una curva de aprendizaje inicial y posibles limitaciones de soporte para algunos lenguajes, sus ventajas en términos de **rendimiento**, generación automática de código y capacidad para construir sistemas distribuidos de **alto rendimiento** lo convierten en una opción atractiva para el desarrollo de aplicaciones modernas. Con el respaldo de una comunidad activa, gRPC continúa evolucionando para abordar estas limitaciones y mejorar su utilidad en diferentes entornos de desarrollo.

## Ejemplo

En este ejemplo se realizó una pequeña aplicación tipo tienda de libros basada en microservicios, la cual cuenta con dos servicios. Uno tiene la responsabilidad de mostrarle al cliente los libros, y el otro se encarga de la lógica para recomendarle al usuario los libros. Ambos servicios están en diferentes tecnologías, pero se comunican mediante el protocolo gRPC.


![Exmaple](https://i.ibb.co/vdCQQ4Q/diagram-drawio.png)

## Referencias

[https://realpython.com/python-microservices-grpc/#example-implementation]
[https://grpc.io/]





