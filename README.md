# Rueda Libre

Sitio web de alquiler de bicicletas en Medellín. El proyecto busca que el usuario pueda conocer la flota, consultar tarifas y reservar una bicicleta de forma fácil, y que descubra nuevas experiencias con los recorridos guiados de la ciudad.

**Sitio publicado:** https://laura-fracica.github.io/rueda_libre/

## Páginas

| Página | Archivo | Contenido |
|---|---|---|
| Inicio | `index.html` | Portada, carrusel de promociones, quiénes somos, servicios, flota, galería de rutas, cómo alquilar, beneficios, ubicación y contacto |
| Tarifas | `paginas/tarifas.html` | Tarifas por hora, medio día y día completo, y planes de recorridos guiados |
| Reservas | `paginas/reservas.html` | Formulario de reserva con validación de campos |
| Catálogo de pruebas | `pruebas/catalogo-bootstrap.html` | Página de prueba con las cards de la flota |

## Funcionalidades

- Navegación con barra superior adaptable a celular, tableta y computador.
- Carrusel de tres promociones con controles anterior y siguiente, y avance automático.
- Flota y galería de rutas en cards de igual altura dentro de una grilla adaptable.
- Tablas de tarifas y de recorridos.
- Formulario de reservas con campos obligatorios, formato de correo y celular, rango de fechas y longitud de texto.
- Botón de WhatsApp siempre visible en la esquina inferior derecha.
- Datos de contacto, horario y enlace al mapa de la tienda.

## Tecnologías

- HTML5 semántico
- CSS3 con variables personalizadas
- Bootstrap 5.3.8 (CSS y JavaScript por CDN)
- Google Fonts: Montserrat para títulos y Open Sans para texto
- GitHub Pages para la publicación

## Identidad visual

| Color | Valor | Uso |
|---|---|---|
| Verde Ruta | `#1F7A4D` | Enlaces y elementos de acento |
| Naranja Pedal | `#F26B21` | Fondos de botones y etiquetas |
| Azul Noche | `#14213D` | Texto principal y estados de foco |
| Crema | `#FFF4E0` | Fondo de la página |
| Gris Asfalto | `#4A4F57` | Texto secundario |

Todas las combinaciones de texto y fondo se verificaron con la relación de contraste WCAG: 4.5:1 para texto normal y 3:1 para texto grande.

## Accesibilidad

- Atributo `lang="es"` en todas las páginas.
- Textos alternativos descriptivos en las imágenes, y vacíos en las decorativas.
- Jerarquía de encabezados ordenada.
- Textos de enlace comprensibles fuera de contexto.
- Navegación completa con teclado y foco visible.
- Texto para lectores de pantalla en los controles del carrusel.

## Estructura del proyecto

```
rueda_libre/
├── index.html
├── css/
│   └── styles.css
├── paginas/
│   ├── tarifas.html
│   └── reservas.html
├── pruebas/
│   └── catalogo-bootstrap.html
└── img/
    └── bitacora.txt
```

La carpeta `img/` también contiene las imágenes del sitio. `img/bitacora.txt` es la bitácora del proyecto, con las pruebas, las decisiones y la auditoría de accesibilidad.

## Ejecutar en local

1. Clona el repositorio:

   ```
   git clone https://github.com/laura-fracica/rueda_libre.git
   ```

2. Abre la carpeta y lanza `index.html` en el navegador, o usa la extensión Live Server de Visual Studio Code.

El sitio necesita conexión a internet para cargar Bootstrap y las fuentes desde sus CDN.

## Autora

Laura Vanesa Fracica Sarmiento