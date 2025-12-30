Portfolio Online – Isaac Piña Portillo
🌐 [Ver Portfolio Online – Isaac Piña Portillo](https://github.com/ISACOMACO/Portfolio_Isaac_Pina_Portillo.git)

Este proyecto consiste en el desarrollo de mi portfolio online personal, creado y diseñado íntegramente por mí.

El portfolio recoge una selección de mis trabajos en diferentes disciplinas creativas, organizados en secciones claras y diferenciada.
Ilustración: Proyectos personales y exploraciones gráficas, presentados con efectos de glassmorphism para dar profundidad y dinamismo.
Diseño gráfico: Branding, identidad visual, composición y comunicación, con presentación ordenada.
Fotografía: Carrusel interactivo de imágenes tomadas por mí, que permite una navegación fluida y visualmente atractiva.
Diseño 3D: Proyectos y experimentos tridimensionales.

La web cuenta con un diseño coherente, que combina tipografía cuidada, paleta de colores consistente y animaciones elegantes, garantizando una experiencia de usuario intuitiva y atractiva.

Funcionalidades Destacadas
Animaciones normales y de scroll: Elementos que se mueven suavemente según la interacción del usuario.
Botón Call to Action: Facilita la navegación hacia secciones clave del portfolio, como contacto o trabajos destacados.
Página 404 personalizada: Incluye una ilustración original, animación de degradado y un botón que devuelve al usuario a la página principal.
Glassmorphism: Aplicado en secciones como Ilustración, para dar profundidad y modernidad visual.
Animación “mover”: Animaciones dinámicas para resaltar contenido.
Carrusel de fotografías: Permite navegar fácilmente por la sección de fotografía.
Footer con contacto: Incluye formulario y enlaces de contacto accesibles desde cualquier sección de la web.

Uso de Inteligencia Artificial
De acuerdo con la política de uso de agentes de IA: toda la creación del código, animaciones, diseño gráfico y contenidos originales fueron realizados por mí. La IA se utilizó únicamente como asistencia para tareas de redacción y organización de la documentación.
Tecnologías Utilizadas
HTML & CSS: Estructura, estilos, animaciones y layout responsive.
JavaScript: Interacciones, animaciones de scroll y carrusel de fotografías.
CSS Avanzado: Glassmorphism, degradados animados, hover effects y transición de elementos.
Responsive Design: Optimización completa para dispositivos móviles y escritorio.

USO DE INTELIGENCIA ARTIFICIAL

Durante el desarrollo se utilizó un asistente de IA para planificar y estructurar el código, siguiendo la política de uso de agentes de IA.

### Política aplicada

- **Fase 1: Planificación**: Antes de implementar cualquier feature, se solicitó a la IA un plan detallado en archivos independientes.
- **Fase 2: Implementación**: Solo después de documentar el plan se pasó a escribir el código.

#Registro de uso de IA:

./Docs/plan1.md
Animaciones ScrollTrigger

Prompt: “Quiero animaciones de elementos desde la izquierda a la derecha al hacer scroll, con código listo para integrar”
Respuesta IA:

- Se explicó cómo usar GSAP y ScrollTrigger:

````javascript
gsap.from(".hero-top", {
  x: -200,
  opacity: 0,
  duration: 1,
  scrollTrigger: ".hero-top"
});

gsap.from(".poster", {
  x: -100,
  opacity: 0,
  duration: 1,
  stagger: 0.2,
  scrollTrigger: ".poster"
});

./Docs/plan2.md
Integración de formulario de contacto / scroll hero

Prompt:“Al hacer click en botón hero, el scroll debe llevar al contacto; incluir ejemplo con smooth scroll”
Respuesta IA:
- Se explicó cómo hacer scroll suave a la sección de contacto usando JavaScript:
```javascript
document.querySelector(".hero-button").addEventListener("click", () => {
  document.querySelector("#contacto").scrollIntoView({ behavior: "smooth" });
});

./Docs/plan3.md
Página 404 con degradado

## Prompt
"Añade un fondo con degradado blanco-negro a la pagina de 404"

## Respuesta IA
- HTML: <section> con mensaje central tipo `<h1>404</h1>` y `<p>Página no encontrada</p>`
- CSS: fondo con `linear-gradient`, centrado vertical y horizontal de texto, tipografía grande y legible
- Sugerencias adicionales: botón de volver al inicio, animaciones leves de entrada del texto

## Implementado
- Página 404 con fondo degradado aplicado
- Mensaje central centrado y estilizado
- Posible botón de regreso al inicio implementado según recomendación


Docs/plan4.md
Glassmorphism en sección de ilustración

## Prompt
"Diseña un efecto glassmorphism para la sección de ilustración usando HTML y CSS, con fondo semitransparente y borde difuminado"

## Respuesta IA
- HTML: <div> para la tarjeta de ilustración con contenido dentro
- CSS:
  - `background: rgba(255,255,255,0.2)` para transparencia
  - `backdrop-filter: blur(10px)` para efecto difuminado
  - `border-radius` y `box-shadow` para realzar el efecto
- Sugerencias: padding y márgenes consistentes, tipografía legible sobre el fondo

## Implementado
- Tarjetas de ilustración con efecto glassmorphism aplicado
- Fondo difuminado con transparencia y sombras
- Contenido interno centrado y responsive

````
