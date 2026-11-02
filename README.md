# Teoría de códigos

Notas sobre códigos correctores de errores: códigos lineales, códigos de Hamming, códigos perfectos, cotas de Hamming y Plotkin, diseños de Hadamard y probabilidad de error. Incluyen implementaciones en Python y ejercicios resueltos.

*Notes on error-correcting codes (in Spanish): linear codes, Hamming codes, perfect codes, the Hamming and Plotkin bounds, Hadamard designs and error probability, with Python implementations and worked exercises.*

**[Leer el PDF](teoria-de-codigos.pdf)** · Francisco Terán · Universidad San Francisco de Quito, mayo de 2025

Escritas como proyecto individual del curso de Combinatoria y Grafos, a partir de Roberts y Tesman, *Applied Combinatorics*.

## Contenido

| § | Tema | Página |
|---|---|---|
| 1 | Transmisión de información: codificación, canal y decodificación | 1 |
| 2 | Codificación por bloques, repetición, permutación y paridad | 3 |
| 3 | Códigos lineales: matriz generadora, matriz de paridad y síndrome | 5 |
| 4 | Códigos de Hamming: construcción, distancia mínima y propiedades | 7 |
| 5 | Códigos perfectos e implementación de Hamming(7,4) en Python | 9 |
| 6 | Distancia de Hamming y límite de Hamming | 12 |
| 7 | Probabilidad de error: canal binario simétrico, comparación de códigos, decodificación por consenso | 14 |
| 8 | Diseños de bloques y códigos de Hadamard | 16 |
| 9 | Límite de Plotkin | 19 |
| 10 | Aplicaciones | 21 |
| 11 | Ejercicios resueltos: codificación y decodificación, corrección de errores, códigos lineales | 22 |

## Notación

La matriz generadora se denota *M* y el código de Hamming H<sub>k</sub> tiene *k* bits de paridad y longitud *n* = 2<sup>k</sup> − 1. En otros textos es común usar *G* para la matriz generadora y *k* para el número de bits de información.

## Referencias

- F. S. Roberts y B. Tesman. *Applied Combinatorics*, 2.ª ed. Chapman and Hall/CRC, 2024.
- R. W. Hamming. Error detecting and error correcting codes. *Bell System Technical Journal*, 29(2):147–160, 1950.

## Licencia

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.es): se puede compartir y adaptar citando la fuente.
