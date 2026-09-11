# Sitio estático de mascotas perdidas

## Estructura

- `index.html`: página principal.
- `estilosIA.css`: todas las reglas CSS.
- `imagenes/`: colocar aquí una imagen por mascota.
- `info/`: colocar aquí el PDF correspondiente a cada mascota.

## Archivos esperados

### Perros
- `imagenes/rocky.jpg` + `info/rocky.pdf`
- `imagenes/luna.jpg` + `info/luna.pdf`
- `imagenes/simon.jpg` + `info/simon.pdf`

### Gatos
- `imagenes/milo.jpg` + `info/milo.pdf`
- `imagenes/nina.jpg` + `info/nina.pdf`
- `imagenes/tom.jpg` + `info/tom.pdf`

## Importante sobre el requisito del select

El sitio no utiliza JavaScript. Un `<select>` HTML por sí solo no puede cambiar dinámicamente el contenido de otra zona de la página sin scripts o procesamiento del servidor.

Por eso se incluyen las dos opciones del select y, además, enlaces estáticos "Perros" y "Gatos" que llevan directamente a cada categoría mediante anchors (`#perros` y `#gatos`). Esto mantiene el sitio 100% estático y funcional sin scripts.

El formulario también es solamente visual: al no existir backend, no procesa ni envía los datos a un servidor.
