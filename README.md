# Rumbo — páginas públicas

Rumbo es una app de finanzas personales para Latinoamérica: registras un gasto escribiéndolo o
dictándolo como lo dirías en voz alta y un coach te dice qué hacer con tu plata, no solo dónde se
fue. *Ponle rumbo a tu plata.*

Este repositorio contiene únicamente las páginas públicas de la app. Son cinco archivos
estáticos: sin dependencias, sin CDN, sin build.

| Archivo | Qué es |
|---|---|
| `index.html` | Portada, con enlaces a las demás. |
| `privacidad.html` | Política de privacidad: qué guarda Rumbo, qué sale de tu teléfono, hacia quién va, cuánto dura y cómo borrarlo todo. |
| `borrar-cuenta.html` | Cómo borrar tu cuenta y tus datos, desde la app o solicitándolo, y qué pasa si ya la desinstalaste. |
| `soporte.html` | Soporte: preguntas frecuentes y a dónde escribir. |
| `estilo.css` | Hoja de estilo compartida. Claro y oscuro. |

## Escribirnos

**Rumboapp05@gmail.com** — soporte, dudas de privacidad y solicitudes sobre tus datos (acceso,
corrección, portabilidad, borrado). Si tu cuenta tiene un correo vinculado, escríbenos desde ese
mismo correo: es la única forma que tenemos de comprobar que la cuenta es tuya.

Contestamos en español, lo antes posible y como máximo en 30 días.

## Cómo se publica

Con **GitHub Pages**, servido desde la rama `main` en la raíz del repositorio
(*Settings → Pages → Deploy from a branch → `main` / `(root)`*). No hay build ni generador: lo que
está en el repositorio es exactamente lo que se sirve.

Para ver las páginas en local basta con abrir cualquiera de los `.html` en el navegador.
