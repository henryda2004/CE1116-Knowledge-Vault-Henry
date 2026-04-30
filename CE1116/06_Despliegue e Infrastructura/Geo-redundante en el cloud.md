---
Fecha de creación: 2026-04-30 08:44
Fecha de Modificación: 2026-04-30 08:44
tags:
  - infraestructura
Tema: cloud-computing
---


## 📚 Idea/Concepto 

La geo-redundancia replica datos y servicios en múltiples regiones geográficas distantes, siendo la base del Disaster Recovery ante fallos regionales catastróficos donde zonas completas quedan inoperativas. La replicación inter-regional es típicamente asincrónica debido a la latencia inherente de la distancia, lo que implica un RPO mayor a cero y un trade-off entre resiliencia y consistencia de datos. Los proveedores mitigan esta latencia mediante redes de backbone de fibra privadas que evitan la congestión de internet pública. Para que el RTO sea efectivo se requieren mecanismos de Global Load Balancing como redirección por DNS o Anycast. Adicionalmente, las tarifas de egress entre regiones representan un costo operativo importante que debe factorizarse en el diseño del sistema.
## 📌 Puntos Claves (Opcional)
- 

## 🔗 Connections
- [[Redundante en zona en el cloud]]
- [[Redundante localmente en el cloud]]
- [[Cloud Híbrido]]
- [[Cloud Público]]

## 💡 Personal Insight (Opcional)
- 
## 🧾 Recursos (Opcional)
- 