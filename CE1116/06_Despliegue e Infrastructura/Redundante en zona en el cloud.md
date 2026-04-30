---
Fecha de creación: 2026-04-30 08:43
Fecha de Modificación: 2026-04-30 08:43
tags:
  - infraestructura
Tema: cloud-computing
---


## 📚 Idea/Concepto 

La redundancia en zona replica datos y servicios en múltiples zonas de disponibilidad dentro de una misma región geográfica. Cada zona tiene aislamiento físico total de energía, red y enfriamiento, lo que evita fallos correlacionados entre ellas. La proximidad entre zonas permite replicación sincrónica con RPO de cero, sin el penalizador de latencia de la redundancia regional. Cuando una zona falla, un balanceador de carga regional redirige el tráfico automáticamente a las zonas restantes. Este modelo es el requisito técnico para alcanzar niveles de disponibilidad superiores al 99.9% en entornos críticos, aunque es insuficiente ante desastres de escala regional que afecten todas las zonas simultáneamente.
## 📌 Puntos Claves (Opcional)
- 

## 🔗 Connections
- [[Redundante localmente en el cloud]]
- [[Geo-redundante en el cloud]]
- [[Escalamiento horizontal y vertical en el cloud]]
- [[Cloud Público]]

## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- 