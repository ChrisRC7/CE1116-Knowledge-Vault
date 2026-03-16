---
Fecha de creación: 2026-03-16 12:16
Fecha de Modificación: 2026-03-16 12:16
tags:
  - Limites_IA
Tema: Límites y Desempeño de Modelos
---


## 📚 Idea/Concepto 
La ventana de contexto es la restricción técnica de diseño que define la longitud máxima de una secuencia de tokens que el mecanismo de auto-atención puede procesar de forma simultánea. Su tamaño está condicionado por la complejidad cuadrática del cómputo de atención, lo que genera un alto costo de procesamiento y latencia.

## 📌 Puntos Claves (Opcional)
- Restricción Técnica: Longitud máxima de secuencia procesable simultáneamente en un solo paso de inferencia.
- Recurso Compartido: Espacio compartido compartidos por entrada de usuario, historial, directivas del sistema y respuestas.
- Complejidad Cuadrática: Su tamaño está limitado principalmente por la complejidad computacional $O(n^2)$.
- Riesgo de Saturación: Excederla puede provocar alucinaciones por recorte hard-coded de datos.

## 🔗 Connections
- [[Tokenización]]
- [[Mecanismo de Atención]]
- [[Alucinaciones]]
- [[Arquitectura Transformer]]

## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- https://notebooklm.google.com/notebook/e961368a-7cc1-4d76-af41-7ef5bf2c8f25