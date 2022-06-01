# ProyectoPaginaWeb01

Página web creada con:
- **HTML:** permite crear la estructura del sitio web mediante etiquetas
- **CSS:** para definir y crear la presentación de del sitio web
- **JavaScript:** añade características que permite establecer acciones interactivas al sitio web
- **PHP:** favorece la conexión entre los servidores y la interfaz de usuario

Este sitio web fue creado y desarrollado usando la plataforma **NetBeans 10.0**. Además está adaptado para ejecutarse en dispositivos móviles.

El archivo **index.html** es el que contiene la página de inicio, la página principal del sitio web.

La página de inicio o principal consta de varias secciones: 
- **Un encabezado:** donde se muestra el logotipo de la organización
- **Una sección principal:** que contiene un mensaje, el menú principal, una sección adaptada para mostrar un enunciado especial, un carrusel de imagenes 
- **Un pie de página:** que muestra la información de la organización

El menú principal consta de cuatro opciones: 
- **Quienes somos:** muestra información acerca de la organización. Integra un submenú con 6 opciones adicionales, las cuales describen aspectos tales como la visión, la misión, los valores, entre otros, de la organización
- **Reflexiones:** muestra una página dedicada a publicar artículos, noticias, mensajes y/o reflexiones bíblicas
- **Actividades:** muestra las actividades que va a realizar la organización durante el mes en curso; así como actividades que se van a realizar a corto plazo 
- **Contáctenos:** consta de dos secciones: un formulario de contacto para que la persona puede ponerse en contacto con la organización y un mapa que muestra la ubicación junto con datos adicionales de contacto

En cada archivo de estilos css se utiliza la técnica de rejilla CSS Grid Layout para organizar de manera más eficiente cada elemento de la interfaz del sitio web, el cual los acomoda tanto a lo largo como a lo ancho de la ventana del navegador. Además, es complementado con flexbox, el cual ayudar a distribuir el espacio entre los ítems de la interfaz y mejora las capacidades de alineación de cada elemento.

Para el formulario de contacto se programaron validaciones tanto del lado cliente realizado con JavaScript; así como del lado del servidor programado con PHP

Para enviar la información del usuario a través del formulario de contacto se utiliza una clase llamada PHPMailer. PHPMailer es una clase php para enviar emails basada en el componente active server ASPMail. Permite de una forma sencilla tareas complejas como por ejemplo:
- Enviar mensajes de correo con ficheros adjuntos (attachments) 
- Enviar mensajes de correo en formato HTML 
- Enviar emails via sendmail, PHP mail(), o con SMTP.

A continuación se presentan algunas imágenes del sitio web brevemente descrito anteriormente:

![01  PaginaInicio_1](https://user-images.githubusercontent.com/98922137/164998988-ea019481-3620-41b1-ad3c-8c9ee3027478.png)

![02  PaginaInicio_2](https://user-images.githubusercontent.com/98922137/164998990-8ab1ea60-6c11-4916-ab07-b121ca85c11e.png)

![03  PaginaInicio_3](https://user-images.githubusercontent.com/98922137/164998991-f5afce89-b181-4b8f-9ba6-490c91a9fa5c.png)

![09  Nuestros valores_1](https://user-images.githubusercontent.com/98922137/164999011-b4120c89-5e0d-495f-8a5b-c39b4eacc8b9.jpg)

![10  Nuestra estrategia_1](https://user-images.githubusercontent.com/98922137/164999012-c8448d6f-79ca-482f-9d76-1ca802b489fd.jpg)

![13  Reflexión_3](https://user-images.githubusercontent.com/98922137/164999055-792f458b-99db-4103-a5d5-f9383bf76778.jpg)

![15  Actividades_2](https://user-images.githubusercontent.com/98922137/164999056-9e0f7f3f-fe9d-4816-9c99-335b3c6aea9b.jpg)

![16  Actividades_3](https://user-images.githubusercontent.com/98922137/164999058-e4cab01d-fabf-4202-9711-43b166a7ffb6.jpg)

![19  Contacto_3](https://user-images.githubusercontent.com/98922137/164999079-bbbdaf7a-e3e6-4d0a-b3a3-ce4d42ef9bbd.jpg)

![20  Contacto_4](https://user-images.githubusercontent.com/98922137/164999081-67a80ff7-6afb-42fd-8db2-972722314c19.jpg)

![22  Contacto_6](https://user-images.githubusercontent.com/98922137/164999599-323c6078-854c-4408-b53e-a3aeb1dc855f.png)

