---
Fecha de creación: 2026-03-16 12:16
Fecha de Modificación: 2026-03-16 12:16
tags:
  - Arquitectura_IA
Tema: Arquitecturas de IA
---


## 📚 Idea/Concepto 
La Arquitectura Transformer es un sistema que abandona la recurrencia para procesar secuencias en paralelo mediante el mecanismo de Self-Attention. Funciona mediante proyecciones de vectores (Query, Key, Value) y Multi-Head Attention, lo que le permite aprender múltiples relaciones semánticas simultáneamente. Para no perder el sentido del orden al trabajar en paralelo, utiliza codificación posicional, permitiendo una comprensión global y escalable del contexto

## 📌 Puntos Claves (Opcional)
- Paralelismo: Abandona el procesamiento secuencial (recurrencia) para procesar secuencias en paralelo.
- Mecanismo Core: Se basa en el mecanismo de Self-Attention para calcular dependencias globales.
- Componentes Struct: Utiliza proyecciones matriciales (Q, K, V) y Multi-Head Attention.
- Noción de Orden: Requiere codificación posicional para no perder el sentido del orden del texto.

## 🔗 Connections
- [[Mecanismo de Atención]]
- [[Ventana de Contexto]]
- [[Embeddings]]

## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- https://notebooklm.google.com/notebook/e961368a-7cc1-4d76-af41-7ef5bf2c8f25