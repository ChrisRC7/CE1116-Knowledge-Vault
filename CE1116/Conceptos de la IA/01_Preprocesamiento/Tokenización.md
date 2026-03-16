---
Fecha de creación: 2026-03-16 12:13
Fecha de Modificación: 2026-03-16 12:13
tags:
  - Preprocesamiento
Tema: Preprocesamiento de Datos de IA
---


## 📚 Idea/Concepto 
La tokenización es el proceso de convertir texto en una secuencia de índices numéricos (integers). Este flujo incluye la fragmentación del texto de entrada en palabras, subwords o caracteres mediante algoritmos como BPE y la inserción de tokens especiales de control, como BOS para marcar el inicio de la secuencia, EOS para el final y PAD para el procesamiento por lotes.

## 📌 Puntos Claves (Opcional)
- Mapeo Numérico: Convierte texto crudo en una secuencia de IDs enteros (tensores).
- Granularidad: Fragmenta en palabras, sub-palabras (como BPE) o caracteres.
- Tokens Especiales: Inserta elementos de control críticos como BOS (inicio), EOS (final) y PAD (procesamiento por lotes).
- Paso Obligatorio: Esencial para que el modelo pueda procesar la entrada.

## 🔗 Connections
- [[Embeddings]]
- [[Ventana de Contexto]]
## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- https://notebooklm.google.com/notebook/e961368a-7cc1-4d76-af41-7ef5bf2c8f25