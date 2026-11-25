# Ozer Betar

![Ozer Betar](assets/logo.png)

Herramienta para los educadores de Betar Uruguay: madrijim, bogrim y la Hanagá, mayores de 18. Responde consultas sobre la ideología y la historia de Betar (Ruaj Betarí, Jabotinsky, símbolos, Shoá, conflicto árabe-israelí) y ayuda a preparar peulot, sijot y material educativo.

No está pensada para que la usen los janijim: ellos reciben el contenido a través de su madrij, en la peulá.

## Fuentes

- **Mishnat Betar — Ideario de Betar Uruguay** (Beta 3.2, Joaquín Salomón). Tiene prioridad en todo lo ideológico.
- **El Libro Azul de Betar.** Se usa para historia y contexto, y como complemento donde Mishnat Betar no llega.

Si las dos fuentes se contradicen en algo ideológico, vale lo que dice Mishnat Betar. Si ninguna de las dos cubre una pregunta, el asistente lo dice.

## Cómo se usa

Preguntale directamente, por ejemplo:

- "¿Qué es el Hadar betarí?"
- "¿Cómo le explico el Monismo a una kvutzá de 12 años?"
- "Preparame una peulá de 1 hora sobre Ki Sheket Hu Refesh para janijim de liceo"
- "¿Qué dice Betar sobre el Shtei Guedot?"
- "¿Qué hizo Betar durante la Shoá?"

## Actualizar las fuentes

Los textos están en `skills/ozer-betar/references/`. El Libro Azul está dividido en un archivo por capítulo dentro de `libro-azul/`. Cuando salga una versión nueva de Mishnat Betar, hay que reemplazar `mishnat-betar.md` (y actualizar `indice.md`).
