# Challenge Testflix

## Testflix Challenge
### Descripción del Proyecto

Este proyecto implica la creación de un Catálogo de Cine interactivo.

La tarea principal es presentar una selección de una película destacada junto con una lista de películas populares obtenidas de una API pública.

Los usuarios tienen la capacidad de actualizar el catálogo añadiendo nuevas películas a una sección llamada "Mis Películas". Actualmente no contamos con un endpoint para este propósito, por lo que es necesario desarrollar una API propia para almacenar y mostrar estas películas.

Nuestro objetivo es que el catálogo completo muestre tanto las películas de la API pública como las de la nueva API que implementemos.

---

### Diseño de la Aplicación
Los prototipos de diseño para escritorio y móvil están disponibles en Figma, accesibles a través de [este enlace](https://www.figma.com/file/SMFjic1EI4T29DcWqmbVfj/Testflix-Challenge?type=design&node-id=0-1&mode=design&t=uMAJLjC590RYVxIv-0).

Después de iniciar sesión en Figma, podrás descargar todos los elementos visuales necesarios.

Es esencial replicar fielmente todos los elementos del diseño con las interacciones y estados visuales correspondientes, como los efectos al pasar el cursor (Hover).

"Agregar Película" es la única función que requiere lógica de programación y desarrollo; los demás botones del menú son decorativos y no funcionales, pero deben estar presentes en el maquetado según aparecen en el diseño.

Cualquier animación o transición en la aplicación es completamente a tu criterio y sería un valor agregado.

---

### Desarrollo Técnico
La función de añadir películas debe permitir cargar una imagen y su título, para después incluir la película en la sección "Mis Películas", accesible a través del menú desplegable de Mis Películas.

Puedes emplear las bibliotecas que prefieras.

El front-end debe ser desarrollado en *VueJs*, usando *Tailwind* para el CSS y el código suministrado debe funcionar correctamente sin errores de consola.

En cuanto a la API, deberás usar *Laravel* y el sistema de gestión de base de datos que prefieras.

Para la evaluación del proyecto, necesitamos que nos proporciones el repositorio con el código de la aplicación (tanto del Front como de la API).

---

### Criterios de Valoración

- Entrega a tiempo
- Concordancia del diseño con la aplicación final
- Funcionamiento óptimo de la aplicación
- Claridad y organización del código
- Diseño responsivo adecuado a distintas resoluciones de pantalla

***

## *Endpoints API Pública*

### *Película Destacada (En el mockup sería “Breaking bad”)*

*[GET]* https://api.themoviedb.org/3/movie/now_playing?api_key=6f26fd536dd6192ec8a57e94141f8b20

### *Populares (Listar las primeras 8 Películas)*

*[GET] [*https://api.themoviedb.org/3/movie/popular?api_key=6f26fd536dd6192ec8a57e94141f8b20](https://api.themoviedb.org/3/movie/popular?api_key=6f26fd536dd6192ec8a57e94141f8b20)

Información acerca del uso de imágenes: https://developers.themoviedb.org/3/getting-started/images

