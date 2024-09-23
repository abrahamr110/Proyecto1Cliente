## ✍🏻 Análisis de los Modelos de Ejecución Cliente/Servidor
#### En el desarrollo de aplicaciones web, existen dos modelos principales de ejecución: Client-Side Rendering (CSR) y Server-Side Rendering (SSR). Cada uno tiene ventajas y desventajas dependiendo del caso de uso y la arquitectura de la aplicación.

#### Client-Side Rendering (CSR):
* En CSR, el contenido HTML se genera en el cliente, es decir, en el navegador del usuario. Cuando se realiza una solicitud de página, el servidor envía un archivo HTML básico junto con archivos JavaScript que luego crean dinámicamente la interfaz de usuario.
* Ejemplo: Aplicaciones creadas con React sin SSR utilizan CSR. La carga inicial puede ser lenta, pero una vez que se ha descargado el código JavaScript, la experiencia del usuario es más interactiva.
* Ventajas: Mayor interactividad, mejor experiencia de usuario después de la carga inicial.
* Desventajas: Mala optimización para motores de búsqueda (SEO) y tiempos de carga inicial más lentos.

#### Comparación:
* CSR es ideal para aplicaciones que requieren mucha interactividad en el cliente, como paneles de control o aplicaciones SPA (Single Page Application).
* SSR es más adecuado para aplicaciones donde el SEO es crucial, como sitios web de comercio electrónico o plataformas como TicketHub, donde los eventos deben ser fácilmente rastreados por motores de búsqueda y las páginas deben cargarse rápidamente.

#### Server-Side Rendering (SSR):
* En SSR, las páginas se renderizan en el servidor y se envían al navegador del usuario como HTML completo. Esto reduce el tiempo de carga inicial y mejora el SEO, ya que los motores de búsqueda pueden leer el contenido renderizado.
* Ejemplo: Usar Next.js con React para generar el HTML en el servidor antes de enviarlo al cliente.
* Ventajas: Mejor SEO, tiempos de carga inicial más rápidos, especialmente útil para contenido dinámico.
* Desventajas: Requiere más recursos en el servidor, lo que puede ser costoso en grandes aplicaciones.

## 📄 Evaluación de los Lenguajes de Programación Web Seleccionados
#### JavaScript
* Ventajas: Es el lenguaje por excelencia para desarrollo frontend, siendo compatible con todos los navegadores y muy flexible. Permite la creación de aplicaciones interactivas en tiempo real.
* Desventajas: Al ser interpretado en el navegador, puede experimentar problemas de rendimiento en aplicaciones de gran escala si no se optimiza correctamente. También puede ser difícil de depurar en entornos más grandes.

#### TypeScript
* Ventajas: Añade tipado estático a JavaScript, lo que ayuda a evitar errores en tiempo de desarrollo y mejora la escalabilidad del código. Facilita la colaboración en proyectos grandes y mantiene el código más limpio y organizado.
* Desventajas: Tiene una curva de aprendizaje más pronunciada, especialmente para desarrolladores que solo están acostumbrados a JavaScript. También puede aumentar el tiempo de desarrollo inicial debido al tipado explícito.

#### Comparación
* JavaScript es más ágil para prototipos y proyectos pequeños, mientras que TypeScript es más adecuado para aplicaciones grandes y proyectos donde se busca minimizar errores de producción y mejorar la mantenibilidad del código.

## 🌐 Estudio sobre la Compatibilidad en Navegadores
#### Uno de los retos más grandes en el desarrollo web es la compatibilidad entre navegadores, ya que no todos los navegadores interpretan el código JavaScript de la misma manera.

#### Problemas comunes
* Soporte limitado de ciertas API de JavaScript en navegadores más antiguos (como Internet Explorer).
* Diferencias en el manejo del DOM y de los eventos entre navegadores.
* Incompatibilidad con tecnologías modernas, como ES6 o ES7, en versiones más antiguas de navegadores.

#### Soluciones:
* Utilizar polyfills: Estos fragmentos de código permiten usar funciones modernas en navegadores que no las soportan nativamente. Por ejemplo, Babel transpila el código moderno de JavaScript a versiones anteriores compatibles con todos los navegadores.
* Herramientas como Can I Use pueden ser útiles para verificar el soporte de las características de JavaScript en diferentes navegadores.
* Usar frameworks como React o Next.js, que optimizan automáticamente el código para asegurar que funcione en la mayoría de los navegadores.

## 🧑🏿‍💻 Mecanismos de Integración de los Lenguajes de Marcas con los Lenguajes de Programación
#### En aplicaciones web modernas, los lenguajes de marcas como HTML se combinan estrechamente con los lenguajes de programación, como JavaScript.

* HTML es la base estructural de cualquier página web, y se complementa con JavaScript para la manipulación dinámica del DOM. Esto permite cambiar el contenido, estilo y estructura de una página web sin tener que recargarla por completo.
* En React, el uso de JSX (una extensión de JavaScript que permite escribir código HTML dentro de JavaScript) facilita la integración del HTML y la lógica de la aplicación.
* Next.js lleva esto un paso más allá, permitiendo renderizar contenido dinámico del lado del servidor (SSR) y luego actualizar la página de manera interactiva en el cliente (CSR).

## ⌨️ Evaluación de Herramientas de Programación para Clientes Web
* VSCode: Es uno de los editores de código más populares, con soporte para JavaScript, TypeScript y React. Además, cuenta con una gran cantidad de extensiones que facilitan el desarrollo, como linters, autoformateadores y depuradores.
  * Ventajas: Seguimiento de cambios, facilidad para colaborar en ramas, integración con CI/CD.
* Webpack: Es una herramienta de empaquetado de módulos que agrupa archivos JavaScript, CSS y otros recursos en paquetes optimizados para el navegador.
  * Ventajas: Optimiza el código, reduce el tamaño de los archivos para mejorar la carga en el navegador y permite usar loaders y plugins para procesar diferentes tipos de archivos.
* Postman: Herramienta para probar y verificar APIs. Ayuda a simular solicitudes HTTP y verificar el correcto funcionamiento de los endpoints del backend.
  * Ventajas: Fácil de usar, permite automatizar pruebas, ideal para verificar integraciones de frontend y backend.

## 📊 Análisis de Mercado y Propuesta de Diferenciación
#### TicketHub compite en un mercado donde existen competidores bien establecidos como StubHub, Ticketmaster y Vivid Seats. Estas plataformas ofrecen una funcionalidad similar, pero presentan desventajas en áreas clave que TicketHub buscará mejorar:
* Comisiones más bajas: Muchas plataformas existentes cobran tarifas elevadas tanto a compradores como a vendedores. TicketHub ofrecerá tarifas más competitivas, atrayendo a ambos públicos.
* Interfaz simple y fluida: A diferencia de la sobrecarga visual y la complejidad de algunas plataformas, TicketHub se centrará en una interfaz optimizada y amigable para mejorar la experiencia del usuario.
* Seguridad mejorada con Blockchain: TicketHub utilizará blockchain para verificar la autenticidad de las entradas, eliminando las posibilidades de fraude en la reventa de tickets.
* Personalización avanzada: TicketHub incorporará algoritmos de recomendación que sugerirán eventos según los intereses y comportamientos de los usuarios, proporcionando una experiencia más personalizada.

