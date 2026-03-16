---
Fecha de creación: 2026-03-16 12:15
Fecha de Modificación: 2026-03-16 12:15
tags:
  - Modelado_IA
Tema: Modelos y Arquitecturas de IA
---


## 📚 Idea/Concepto 
La función de activación es un hiperparámetro crítico que aplica una transformación no lineal a la suma ponderada de una neurona. Su propósito es permitir que la red modele relaciones complejas y sea entrenable mediante el cálculo de gradientes (diferenciabilidad). Mientras que ReLU es el estándar de eficiencia en redes profundas generales, arquitecturas modernas de LLMs prefieren funciones como GELU o SwiGLU. Finalmente, funciones como Softmax en la capa de salida son esenciales para transformar estas activaciones en distribuciones de probabilidad legibles.

## 📌 Puntos Claves (Opcional)
- No Linealidad: Aplica una transformación no lineal a la suma ponderada de una neurona para modelar datos complejos.
- Hiperparámetro Crítico: Es una decisión de diseño definida manualmente en el modelo.
- Entrenabilidad: Debe ser diferenciable para permitir el cálculo de gradientes.
- Estándares Variados: ReLU para eficiencia general, GELU/SwiGLU para LLMs, Softmax para capas de salida.

## 🔗 Connections
- [[Redes Neuronales]]
- [[Arquitectura Transformer]]

## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- https://notebooklm.google.com/notebook/e961368a-7cc1-4d76-af41-7ef5bf2c8f25