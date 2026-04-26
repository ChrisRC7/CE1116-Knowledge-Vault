---
Fecha de creación: 2026-04-25 20:35
Fecha de Modificación: 2026-04-25 20:35
tags:
  - Disponibilidad
  - Almacenamiento
Tema: Resilencia de Datos
---


## 📚 Idea/Concepto 
La Redundancia de Zona (ZRS) es una estrategia de almacenamiento de alta disponibilidad que utiliza la replicación sincrónica de datos entre múltiples Zonas de Disponibilidad (AZs) dentro de una misma región geográfica. Al garantizar un RPO (Recovery Point Objective) de cero, asegura que no exista pérdida de datos tras el fallo total de una zona, la cual posee aislamiento físico y lógico de alimentación, red y enfriamiento. Sin embargo, su implementación conlleva un trade-off de latencia, ya que la replicación sincrónica entre distancias físicas penaliza el rendimiento de escritura. Económicamente, implica un costo superior al modelo local y posibles cargos por transferencia de datos inter-zonal, pero es el estándar para cargas de trabajo críticas que requieren resiliencia ante desastres naturales locales.

## 📌 Puntos Claves (Opcional)
- Utiliza replicación sincrónica entre múltiples Zonas de Disponibilidad (AZs) en la misma región.
- Cada AZ tiene aislamiento físico y lógico de alimentación, red y enfriamiento.
- Garantiza un RPO de cero ante el fallo total de una zona.
- Introduce un trade-off de latencia y un mayor costo comparado al modelo local.

## 🔗 Connections
- [[Redundante localmente en el cloud]]
- [[Redundante geo-redundante en el cloud]]
- [[IaaS vs PaaS vs SaaS]]]
- [[Escalamiento horizontal y vertical en el cloud]]

## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- https://notebooklm.google.com/notebook/47f01753-557c-408b-b663-7083c7c19547