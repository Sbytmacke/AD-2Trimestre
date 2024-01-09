# Informe Breve sobre Elección de Tecnologías para API REST
## Elección de Tecnologías

Utilizamos MongoDB, Python y Docker para desarrollar una API REST debido a sus características clave y ventajas comparativas frente a otras tecnologías punteras.

## MongoDB
- Ideal para esquemas flexibles y manejo sencillo de grandes volúmenes de datos.

### MongoDB vs. Bases de Datos Relacionales:
- Las bases de datos relacionales pueden ser menos adaptables y más complejas.

### MongoDB vs. Otras Bases de Datos No Relacionales

- Cassandra: emplea un modelo de columna similar a los esquemas de Bases Datos Relacionales, destaca en escalabilidad y tolerancia a fallos.
- Redis: enfocada en almacenamiento en memoria, ideal para aplicaciones que requieren alta velocidad.
- CouchDB: utiliza un modelo basado en documentos similar a MongoDB, pero con énfasis en la replicación y sincronización entre nodos.

En conclusión, la elección principal de utilizar MongoDB es debido a su modelo de documentos flexibles y sin esquema fijo, siendo una de las bases de datos más sencilla de implementar y desarrollar.

## Python
- Sintaxis clara y versatilidad.

- Abundancia de bibliotecas y frameworks, como Flask y Django, para construir APIs de manera eficiente.

### Python vs. Otros Lenguajes:
- La sintaxis clara de Python y su amplio ecosistema se convierte en un lenguaje rico en comparación a lenguajes como Java o C#.

## Docker
- Empaqueta la aplicación y sus dependencias para un despliegue en diferentes entornos.

- Escalabilidad y Orquestación: gestión de contenedores con herramientas como Docker Compose.

### Docker vs. Máquinas Virtuales:
- Docker supera a las máquinas virtuales en eficiencia y velocidad, proporcionando una gestión más ligera y flexible, gracias a que los contenedores comparten el S.O. anfitrión.
  
