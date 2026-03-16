---
Fecha de creación: 2026-03-16 12:16
Fecha de Modificación: 2026-03-16 12:16
tags:
  - Arquitectura_IA
Tema: Arquitecturas de IA
---


## 📚 Idea/Concepto 
El mecanismo de atención es un proceso de álgebra lineal que transforma embeddings estáticos en representaciones dinámicas. Utiliza proyecciones matriciales aprendibles para generar vectores Query, Key y Value. La importancia de cada token se calcula mediante una función de compatibilidad entre la Query y la Key, normalizada con un factor de escala para estabilizar gradientes y una función softmax. Se implementa como Multi-Head Attention para paralelizar el aprendizaje y puede incluir máscaras causales para restringir el flujo de información en tareas autorregresivas.

## 📌 Puntos Claves (Opcional)
- Motor del Transformer: Transforma embeddings estáticos en representaciones contextuales dinámicas.
- Cálculo de Relevancia: Calcula pesos de importancia entre tokens mediante una función de compatibilidad entre Query y Key.
- Estabilización Matemática: Se normaliza con softmax y factores de escala para estabilizar gradientes.
- Costo Computacional: Crece cuadráticamente cuadráticamente con el tamaño de la ventana de contexto.

## 🔗 Connections
- [[Arquitectura Transformer]]
- [[Embeddings]]
- [[Ventana de Contexto]]

## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- https://notebooklm.google.com/notebook/e961368a-7cc1-4d76-af41-7ef5bf2c8f25