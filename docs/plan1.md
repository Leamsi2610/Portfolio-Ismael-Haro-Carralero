# IMÁGENES EN EL EFECTO PARALLAX

# PROMPT A LA IA

- ¿Cómo puedo meter una imagen en el parallax de una web?

# RESPUESTA DE LA IA

- La IA propuso separar la imagen del efecto parallax, utilizando una etiqueta <img> dentro del contenedor, en lugar de usar background-image en CSS. El efecto visual se controla mediante propiedades como object-fit: cover y object-position para evitar recortes indeseados. El contenido se mantiene encima mediante z-index, y se añade una capa de overlay con pseudo-elementos para mejorar la legibilidad del texto.

# IMPLEMENTACIÓN

- Se implementó el uso de una etiqueta <img> para la imagen parallax definida en el index.html. Se aplicó object-fit: cover y object-position para controlar el recorte de la imagen. El contenido textual se colocó sobre la imagen mediante z-index y se añadió una capa de color semitransparente para mejorar la legibilidad.
