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

## Bajo cifrado (beta)

Página aparte, `bajocifrado.html`, pensada para el celular. Se escribe el tenor, el contralto y el soprano sobre un bajo cifrado dado, con una paleta inferior (acorde y voz con flechas, las 7 notas y la octava). Ejercicios cortos (17 fórmulas) en 4 niveles: estado fundamental, primera inversión, 6/4 cadencial y séptima de dominante, en 9 tonalidades mayores.

- **Comprobar:** revisa registro, voces cruzadas, espaciado, notas ajenas al acorde, acorde completo, duplicaciones, quintas y octavas paralelas (y directas), sensible, séptima y 6/4 cadencial. Toca un problema para verlo resaltado en el pentagrama.
- **Pista y Solución:** un solucionador busca una realización sin errores que respeta lo ya escrito y la muestra como notas "fantasma" punteadas.
- **Teoría:** cada fórmula tiene su explicación (qué es, cómo se usa, qué cuidar, qué significan las cifras y un ejemplo en Do mayor con audio). Se abre sola la primera vez que practicas cada ejercicio y después con el botón "i". Hay además una guía general de cadencias desde el menú.
- **Primer acorde invertido:** I⁶ – IV – V – I, I⁶ – V – I e I⁶ – V⁷ – I, además de las otras inversiones de los niveles 2 y 4.
- Se guardan la sesión y el progreso en el navegador; las claves de la partitura usan Noto Music (SIL OFL 1.1) incrustada.

## Repaso inteligente

Cada escala, intervalo o posición de la guitarra tiene un peso: fallar lo sube y acertar lo baja. Al armar una sesión, lo que más fallas sale con más frecuencia, y cada menú muestra "Para repasar" con tus puntos débiles.

## Uso

Abre `index.html` en el navegador (o publícalo con GitHub Pages).
