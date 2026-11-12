# Entropía del lenguaje: tres páginas

| Archivo | Qué hace |
| --- | --- |
| `entropia-letras.html` | F₁ por frecuencia de letras de un texto pegado (con fragmentos del Quijote y de Austen). |
| `entropia-ngramas.html` | F₀, F₁, F₂, F₃ por conteo de letras, digramas y trigramas; carga el Quijote o Austen completos, o un .txt propio. |
| `juego-shannon.html` | Juego de adivinanzas de Shannon: cotas superior e inferior de F_N, texto reducido, histogramas y códigos para juntar los resultados del curso. |

## Cómo publicarlas

1. Sube la carpeta completa al repositorio de tu GitHub Pages, por ejemplo como `entropia/`.
2. La carpeta `texts/` debe quedar junto a los HTML: `entropia-ngramas.html` y `juego-shannon.html` cargan de ahí los corpus.
3. Las direcciones quedan así: `https://jjaimero.github.io/entropia/juego-shannon.html` (y análogas).

Si abres los archivos con doble clic desde tu disco, los botones de corpus completos no funcionan: el navegador bloquea la carga de archivos locales. Para probar en tu computador, abre una terminal en la carpeta y ejecuta `python3 -m http.server`; luego visita `http://localhost:8000`.

## Textos

Todos son de dominio público, tomados de Project Gutenberg (se les quitó el encabezado y el pie de Gutenberg):

- `quijote.txt`: Miguel de Cervantes, *Don Quijote* (1605).
- `samper.txt`: José María Samper, *Viajes de un colombiano en Europa* (1862).
- `marianela.txt`: Benito Pérez Galdós, *Marianela* (1878).
- `prideprejudice.txt`: Jane Austen, *Pride and Prejudice* (1813).
