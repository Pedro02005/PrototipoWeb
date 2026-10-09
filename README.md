# AdminExpress - Página de Login

Práctica de HTML y CSS para representar una página de inicio de sesión a partir del diseño de referencia de la actividad. La página utiliza CSS Grid y media queries para adaptar la distribución a computadoras, tabletas y celulares.

## Tecnologías utilizadas

- HTML5 para la estructura y el formulario.
- CSS3 para colores, tamaños y espaciado.
- CSS Grid para las dos columnas de la página.
- Flexbox para centrar el contenido y alinear los iconos con los campos.
- Media queries para modificar el diseño según el ancho de la pantalla.

## Archivos

| Archivo | Descripción |
| --- | --- |
| `index.html` | Contiene el nombre AdminExpress y el formulario de inicio de sesión. |
| `styles.css` | Contiene los estilos y las reglas para tabletas y celulares. |

## Cómo abrir la página

1. Descarga el proyecto o clona el repositorio.
2. Mantén `index.html` y `styles.css` en la misma carpeta.
3. Abre `index.html` en un navegador.

También puedes abrir la carpeta en Visual Studio Code y utilizar la extensión Live Server. No es necesario instalar dependencias ni compilar el proyecto.

## Diseño responsive

| Ancho de pantalla | Distribución |
| --- | --- |
| Más de 850 px | Dos columnas del mismo ancho: panel azul y formulario. |
| De 601 a 850 px | Panel azul al 40% y formulario al 60%. El título AdminExpress se reduce. |
| Hasta 600 px | Se oculta el panel azul y se muestra únicamente el formulario. Se ajustan el espaciado y el tamaño del título. |

Para revisar estos cambios, reduce el ancho de la ventana o utiliza el modo de dispositivos de las herramientas de desarrollo del navegador.

## Formulario

Incluye campos de correo electrónico y contraseña, un botón Sign In y enlaces de recuperación de contraseña y registro. HTML comprueba que los campos no estén vacíos y que el correo tenga un formato válido al enviar el formulario.

El proyecto representa la interfaz visual. No está conectado a un servidor y no autentica usuarios. Los enlaces de recuperación y registro utilizan `#` como destino provisional.
