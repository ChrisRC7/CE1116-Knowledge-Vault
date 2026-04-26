---
Fecha de creación: 2026-04-25 20:31
Fecha de Modificación: 2026-04-25 20:31
tags:
  - Disponibilidad
  - Almacenamiento
Tema: Resilencia de Datos
---


## 📚 Idea/Concepto 
La Redundancia Local (LRS) es una estrategia de almacenamiento basada en la replicación sincrónica de datos dentro de un único centro de datos. Garantiza la durabilidad de la información al distribuir tres copias en distintos dominios de falla (racks independientes con red y alimentación separadas), lo que permite un RPO (Recovery Point Objective) de cero ante fallos de hardware local. Aunque ofrece la menor latencia y es la opción más económica, su diseño prioriza la integridad del dato (durabilidad) sobre el acceso continuo ante desastres mayores (disponibilidad), siendo el modelo ideal para cargas de trabajo transitorias o datos fácilmente reconstruibles que no requieren resiliencia geográfica.causales para restringir el flujo de información en tareas autorregresivas.

## 📌 Puntos Claves (Opcional)
- Aplica replicación sincrónica dentro de un único centro de datos.
- Distribuye copias en distintos dominios de falla (racks independientes).
- Garantiza un RPO (Recovery Point Objective) de cero ante fallos de hardware local.
- Prioriza la durabilidad del dato sobre la disponibilidad ante desastres mayores.

## 🔗 Connections
- [[Redundante en zona en el cloud]]
- [[Redundante geo-redundante en el cloud]]
- [[Cloud Público]]
- [[IaaS vs PaaS vs SaaS]]
- [[Escalamiento horizontal y vertical en el cloud]]
- [[Virtual Private Cloud (VPC)]]

## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- https://notebooklm.google.com/notebook/47f01753-557c-408b-b663-7083c7c19547