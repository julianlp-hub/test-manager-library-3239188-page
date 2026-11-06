# test-manager-library-3239188-page

Sitio público estático de presentación de *Manager Library* (T-23).

## Qué es

Una sola página (`index.html`) que presenta el producto: qué hace, para quién y cuáles son
sus reglas principales. No usa la API ni necesita servidor.

## Evidencia (T-23)

| Comprobación | Cómo |
|---|---|
| Se abre sin la API | Doble clic en `index.html` |
| Correcto en móvil y escritorio | Diseño con `viewport` y rejilla adaptable; probar con el modo móvil del navegador |
| Modo claro y oscuro | Sigue la preferencia del sistema |

## Decisiones

- HTML y CSS en un solo archivo, sin dependencias ni librerías.
- Textos en español; contenido tomado de la sección de alcance del spec.
- No muestra datos personales ni conecta con la API.

## Estado

Entregado: `index.html`.