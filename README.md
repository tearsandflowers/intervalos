# Práctica musical

App web de un solo archivo (`index.html`, sin dependencias) para practicar teoría musical desde el móvil o el navegador. Los datos se guardan en `localStorage`.

## Juegos

- **Escalas** — construye escalas mayores y menores de tónica a tónica, o identifica su armadura (sostenidos y bemoles).
- **Intervalos** — cuatro ejercicios:
  - *Encontrar la nota* e *Identificar*: intervalos por número (2ª a 7ª) sobre Do–Si.
  - *Con cualidad: nota* e *intervalo*: mayor, menor, justa, aumentada y disminuida, con notas que llevan ♯ o ♭.
- **Guitarra** — dos ejercicios, ambos con zona del mástil configurable (trastes 0–5 o 0–12):
  - *Notas en el mástil*: una cuerda y un traste marcados; eliges la nota entre 4 opciones (por cuerdas, con o sin alteraciones). Al responder, el círculo muestra el nombre de la nota.
  - *Intervalos en el mástil*: dos notas en formas naturales de la mano (a 3 trastes o menos y a 2 cuerdas o menos, como en un acorde de cejilla); eliges el intervalo (2ª menor/mayor, 3ª menor/mayor, 4ª justa, 5ª justa u octava). La nota de referencia es la más grave. Los círculos pueden llevar el nombre de la nota (opcional; si se ocultan, salen al responder). Puedes elegir qué intervalos practicar y en qué cuerda va la referencia.

- **Ear Training** — suenan dos notas y reconoces el intervalo (2ª menor a octava; el tritono en el nivel completo). Tres niveles, y puedes elegir si suenan ascendentes, descendentes o juntas. El audio se sintetiza en el navegador con Web Audio (sin archivos de sonido, funciona sin internet); en iPhone hay que desactivar el modo silencio.

## Repaso inteligente

Cada escala, intervalo o posición de la guitarra tiene un peso: fallar lo sube y acertar lo baja. Al armar una sesión, lo que más fallas sale con más frecuencia, y cada menú muestra "Para repasar" con tus puntos débiles.

## Uso

Abre `index.html` en el navegador (o publícalo con GitHub Pages).
