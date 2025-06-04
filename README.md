# Análisis Exploratorio y Sistema de Recomendación de Productos en Amazon

Este proyecto se centra en el análisis de un conjunto de datos de ventas de Amazon, que incluye más de 1,000 valoraciones y reseñas de productos. El objetivo principal es explorar y comprender el comportamiento de los consumidores, identificar productos destacados y desarrollar un sistema de recomendación eficiente.

## Objetivos del Proyecto

1. **Exploración de Valoraciones y Reseñas**: Detectar productos y categorías con mejor desempeño.
2. **Análisis de Sentimientos**: Identificar fortalezas y debilidades de los productos a través del sentimiento del consumidor.
3. **Desarrollo de un Sistema de Recomendación**: Crear un sistema inteligente basado en contenido y comportamiento de los usuarios.

## Aplicaciones del Proyecto

### Análisis de Sentimientos
Clasificación de reseñas en positivas, negativas o neutras para entender la percepción del cliente.

### Sistemas de Recomendación
Construcción de sistemas basados en filtrado colaborativo y análisis de contenido para sugerir productos relevantes.

Este conjunto de datos es una fuente valiosa para extraer información clave sobre el comportamiento del consumidor, apoyar la toma de decisiones comerciales y aplicar técnicas de análisis de datos.

## Diccionario de Datos

| Nombre de Columna   | Descripción                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| `product_id`        | Identificador único para cada producto listado en Amazon.                   |
| `product_name`      | Nombre del producto tal como aparece listado en Amazon.                     |
| `category`          | Categoría o tipo de producto (por ejemplo, electrónica, ropa, etc.).        |
| `discounted_price`  | Precio actual del producto después de aplicar cualquier descuento.          |
| `actual_price`      | Precio original del producto antes de aplicar descuentos.                   |
| `discount_percentage`| Porcentaje de descuento aplicado al producto.                              |
| `rating`            | Calificación promedio del producto basada en la opinión de los clientes.    |
| `rating_count`      | Número total de calificaciones recibidas por el producto.                   |
| `about_product`     | Descripción breve o aspectos destacados del producto.                       |
| `user_id`           | Identificador único para cada usuario que dejó una reseña.                  |
| `user_name`         | Nombre mostrado del usuario que dejó la reseña.                             |
| `review_id`         | Identificador único para cada reseña enviada por los usuarios.              |
| `review_title`      | Título de la reseña del usuario para el producto.                           |
| `review_content`    | Contenido completo de la reseña del usuario, detallando su experiencia con el producto. |
| `img_link`          | Enlace URL a la imagen del producto tal como se muestra en Amazon.          |
| `product_link`      | Enlace URL a la página del listado del producto en Amazon.                  |

### Nota:
 - Al final del código se encuentran las conclusiones del proyecto, en donde se resumen los hallazgos principales y se plantean posibles mejoras o extensiones del análisis realizado.
 - Para su elaboración se hizo uso de herramientas de inteligencia artificial como apoyo en la generación de código, así como de librerías especializadas en análisis de datos y visualización.
