---
Fecha de creación: 2026-04-25 20:26
Fecha de Modificación: 2026-04-25 20:26
tags:
  - Escalabilidad
  - Cloud
Tema: Operaciones en la Nube
---


## 📚 Idea/Concepto 
El escalamiento en el cloud es la gestión elástica de recursos para satisfacer la demanda mediante APIs. El escalamiento vertical (Scale-Up) aumenta la capacidad de recursos (CPU, RAM) de una instancia, enfrentando un techo físico de hardware y generando downtime durante la reconfiguración. El escalamiento horizontal (Scale-Out) añade nodos de forma dinámica, lo cual requiere aplicaciones de preferencia stateless (sin estado) para garantizar la consistencia, un Cloud Load Balancer para la distribución de tráfico y una capa de orquestación para la automatización. En arquitecturas modernas, el cómputo y el almacenamiento se desacoplan para escalar de forma independiente, permitiendo incluso el uso de escalamiento predictivo basado en IA para anticipar picos de demanda.

## 📌 Puntos Claves (Opcional)
- Vertical (Scale-Up): Aumenta CPU/RAM de una instancia, pero enfrenta límites físicos y genera downtime
- Horizontal (Scale-Out): Añade nodos dinámicamente; prefiere aplicaciones stateless (sin estado).
- El escalamiento horizontal requiere orquestación y un Cloud Load Balancer.
- El desacoplamiento de cómputo y almacenamiento permite el escalamiento predictivo con IA.

## 🔗 Connections
- [[Cloud Público]]
- [[Virtual Private Cloud (VPC)]]
- [[Redundante en zona en el cloud]]

## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- https://notebooklm.google.com/notebook/47f01753-557c-408b-b663-7083c7c19547