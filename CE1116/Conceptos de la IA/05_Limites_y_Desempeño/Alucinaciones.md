---
Fecha de creación: 2026-03-16 12:16
Fecha de Modificación: 2026-03-16 12:16
tags:
  - Limites_IA
Tema: Límites y Desempeño de Modelos
---


## 📚 Idea/Concepto 
Son un fenómeno derivado de la naturaleza estocástica de los LLMs, donde el modelo genera secuencias de tokens factualmente incorrectas o patrones inexistentes que mantienen coherencia gramatical. Ocurren porque el sistema predice salidas mediante asociaciones estadísticas y pesos aprendidos en lugar de consultar una base de datos de hechos. Su aparición está ligada a la calidad del dataset de entrenamiento (ruido o sesgos), a la configuración de parámetros como la temperatura y a la estructura del prompt.

## 📌 Puntos Claves (Opcional)
- Naturaleza Estocástica: Es un fenómeno derivado de la predicción de tokens por probabilidad, no de lógica de veracidad.
- Disfraz Gramatical: Generan secuencias gramaticalmente coherentes y superficialmente confiables, pero factualmente incorrectas.
- Causas Múltiples: Vinculadas a la calidad del dataset (ruido, sesgos), la temperatura y la estructura del prompt.
- Fallo Probabilístico: Resultan de fallos probabilísticos en el cálculo de atención sobre los embeddings.

## 🔗 Connections
- [[Ventana de Contexto]]
- [[Función de Activación]]
- [[Embeddings]]

## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- https://notebooklm.google.com/notebook/e961368a-7cc1-4d76-af41-7ef5bf2c8f25