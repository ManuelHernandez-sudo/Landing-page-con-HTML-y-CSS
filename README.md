# Trigo y Luna — Landing page

Página de aterrizaje para **Trigo y Luna**, una panadería artesanal ficticia
que amasa al anochecer, fermenta durante la noche y hornea justo antes del
amanecer. El sitio presenta el proceso de horneado, una selección de panes y
la información de contacto y horario.

Construida solo con **HTML5 semántico** y **CSS3** (sin JavaScript, sin
frameworks).

## Estructura del proyecto

```
/
├── index.html
├── styles.css
├── assets/
│   ├── logo-luna-trigo.svg
│   └── pan-artesanal.svg
└── README.md
```

## Cómo ejecutar la página

1. Clona o descarga este repositorio.
2. Ábrelo en Visual Studio Code o Cursor.
3. Instala la extensión **Live Server** (si no la tienes) desde la pestaña de
   extensiones.
4. Haz clic derecho sobre `index.html` y selecciona **"Open with Live
   Server"**, o pulsa el botón **"Go Live"** en la barra inferior.
5. El navegador abrirá automáticamente `index.html` en una dirección local
   (por ejemplo `http://127.0.0.1:5500`).

También puedes abrir `index.html` directamente en el navegador con doble
clic, aunque se recomienda Live Server para recargar los cambios en vivo.

## Notas de diseño

- Tipografías: **Fraunces** (títulos), **Work Sans** (texto) y **Space Mono**
  (horarios y etiquetas utilitarias), cargadas desde Google Fonts.
- Paleta: azul noche, ámbar masa, dorado trigo y crema harina.
- El "reloj de horneado" en la sección de inicio y la lista numerada en
  "Proceso" reflejan la secuencia real de elaboración del pan (amasado →
  fermentación → horneado → listo), por lo que el orden numerado tiene un
  propósito informativo y no solo decorativo.
- El diseño es responsivo e incluye estados de foco visibles para navegación
  con teclado.
