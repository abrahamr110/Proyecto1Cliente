# TicketHub - Plataforma de Compra y Venta de Entradas 🎟️

### ✍🏻 Descripción
* TicketHub es una plataforma web diseñada para ofrecer una forma sencilla y eficiente de comprar y vender entradas para eventos en vivo, tales como conciertos, deportes, teatro y más. Los usuarios pueden buscar eventos, comparar precios, comprar entradas directamente y revender sus propias entradas de forma segura. Nuestro objetivo es facilitar el acceso a eventos de entretenimiento con una experiencia de usuario optimizada, centrada en la seguridad de las transacciones y la diversidad de eventos.

### 🕴️ Audiencia objetivo
* Nuestro público objetivo son personas interesadas en asistir a eventos en vivo, como conciertos, partidos deportivos, obras de teatro y festivales. La aplicación está dirigida a usuarios de entre 18 y 45 años, que prefieren realizar sus compras en línea y también a aquellos que desean vender entradas de forma segura, evitando fraudes comunes en la reventa de tickets.

### 📄 Características
* Autenticación de usuarios: Registro e inicio de sesión mediante correo electrónico o redes sociales.
* Gestión de eventos: Búsqueda de eventos por categorías, ubicación, fechas o precios.
* Compra de entradas: Integración con plataformas de pago seguras como PayPal y Stripe.
* Reventa de entradas: Los usuarios pueden vender entradas con comisiones justas.
* Reseñas y calificaciones: Sistema para calificar vendedores y compradores.
* Notificaciones personalizadas: Alertas de eventos cercanos y recomendaciones basadas en preferencias del usuario.
* Seguridad: Encriptación de datos y autenticación de dos factores para garantizar transacciones seguras.

### 🧑🏻‍💻 Tecnologías utilizadas:
#### Frontend
* React con Next.js para el soporte de Server-Side Rendering (SSR), lo que mejora la velocidad de carga y el SEO.
* Tailwind CSS o Bootstrap para un diseño moderno y responsivo.

#### Backend
* Node.js con Express para manejar la lógica de servidor de manera eficiente.
* MongoDB (NoSQL) como base de datos, ideal para manejar grandes volúmenes de datos no estructurados.

#### Justificación
* Las tecnologías seleccionadas, como React, Next.js, Node.js y MongoDB, permiten crear una aplicación escalable y de alto rendimiento, con una experiencia de usuario fluida y segura.

### ⚙️ Modelos de ejecución
#### La aplicación utiliza una combinación de Server-Side Rendering (SSR) y Client-Side Rendering (CSR):
* SSR permite una carga inicial rápida de las páginas y mejora el SEO.
* CSR ofrece una experiencia más dinámica e interactiva en el cliente una vez que la página está cargada.

### ⌨️ Lenguajes de programación
#### JavaScript y TypeScript
* JavaScript: Es el estándar de la web para interacciones rápidas y en tiempo real.
* TypeScript: Aporta tipado estático, lo que mejora la seguridad y escalabilidad del código en aplicaciones grandes.

###  Integración de Lenguajes
#### HTML: Se utiliza para la estructura de la aplicación.
* JavaScript/React: Se utiliza para gestionar la lógica de la aplicación y la manipulación del DOM de manera dinámica.
* Next.js (SSR): Renderiza el HTML en el servidor para mejorar la velocidad de carga y el SEO.

### Herramientas de Desarrollo
* VSCode: Editor de código ligero con soporte para JavaScript, TypeScript y React.
* GitHub: Para el control de versiones y la colaboración entre desarrolladores.
* Postman: Para la verificación y pruebas de las APIs.
* Webpack: Para optimizar el empaquetado de JavaScript y CSS en la aplicación.

### Compatibilidad en Navegadores
#### La aplicación está diseñada para ser compatible con todos los navegadores modernos (Chrome, Firefox, Edge, Safari). Para garantizar esta compatibilidad:
* Se utilizarán polyfills para asegurarse de que las nuevas características de JavaScript funcionen en navegadores más antiguos.
* Babel ayudará a convertir el código JavaScript moderno en versiones compatibles.
* Tailwind CSS asegura la compatibilidad con la mayoría de los navegadores y facilita el diseño responsivo.
