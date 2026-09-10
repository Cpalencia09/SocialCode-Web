# BYSC — Be Your Social Code

Sitio de **Be Your Social Code**: software, automatización e IA desde Caracas.

🔗 https://cpalencia09.github.io/SocialCode-Web/

## Qué es

Una sola página autónoma, sin build ni dependencias: todo el CSS y el JS van en línea
dentro de `index.html`. Lo único externo son las tipografías de Google Fonts
(Archivo, Poppins y JetBrains Mono).

- 5 secciones: inicio, servicios, nosotros, portafolio y contacto.
- Tema claro (`paper`) y oscuro (`ink`), con el logo alternando según el tema.
- Idioma español / inglés.
- Acordeón de servicios, filtro de portafolio y formulario de contacto.

## Estructura

```
index.html    el sitio completo
assets/       logos y texturas
```

## Desarrollo

No hace falta compilar nada. Para verlo en local, servilo por HTTP para que
carguen los assets relativos:

```bash
python -m http.server 8765
```

Y abrí http://127.0.0.1:8765

## Publicación

GitHub Pages sirve la rama `main` desde la raíz. Cada push a `main` actualiza el sitio.

## Pendiente

El formulario de contacto muestra la confirmación pero todavía no envía a ningún
lado: falta conectarlo a un backend, correo o WhatsApp.
