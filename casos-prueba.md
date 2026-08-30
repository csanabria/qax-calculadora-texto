# Escribe 5 casos de prueba para la calculadora de texto (texto normal, texto vacío, solo espacios, una sola palabra, texto con puntuación)

## Casos de prueba para la calculadora de texto


```md
# Casos de prueba para la calculadora de texto

## 1. Texto normal
- Entrada: "Hola mundo desde la calculadora"
- Resultado esperado:
  - Caracteres sin espacios: 27
  - Palabras: 6
  - Oraciones: 1
  - Párrafos: 1
  - Palabra más larga: "calculadora"
  - Palabra más corta: "la"

## 2. Texto vacío
- Entrada: ""
- Resultado esperado:
  - Caracteres sin espacios: 0
  - Palabras: 0
  - Oraciones: 0
  - Párrafos: 0
  - Palabra más larga: —
  - Palabra más corta: —

## 3. Solo espacios
- Entrada: "     "
- Resultado esperado:
  - Caracteres sin espacios: 0
  - Palabras: 0
  - Oraciones: 0
  - Párrafos: 0
  - Palabra más larga: —
  - Palabra más corta: —

## 4. Una sola palabra
- Entrada: "JavaScript"
- Resultado esperado:
  - Caracteres sin espacios: 10
  - Palabras: 1
  - Oraciones: 1
  - Párrafos: 1
  - Palabra más larga: "JavaScript"
  - Palabra más corta: "JavaScript"

## 5. Texto con puntuación
- Entrada: "Hola, mundo! Adios."
- Resultado esperado:
  - Caracteres sin espacios: 19
  - Palabras: 3
  - Oraciones: 2
  - Párrafos: 1
  - Palabra más larga: "mundo!" o "Adios." (empate)
  - Palabra más corta: "Hola,"
```