# Ten en cuenta que...

Para realizar  `GET` o `POST` es necesario mandar en los **headers** la **key** de `Authorization` con el **value** `Token TokenPropocionadoPorMonitor`

```
{
  "Authorization": "Token TokenPropocionadoPorMonitor",
  "Content-Type": "application/json"
}
```


## ¿Dónde puedo encontrar el Token?
El token es único por servicio proporcionado por Monitor, y deberá de ser único por entidad o empresa

## Más Informacion
En caso de requerilo podemos compartir las siguientes etiquetas de información:

 - "workstation": estación de trabajo o máquina a monitorear '"date": fecha que se genera la información "part serial": sku o número de identificación de la parte "part count": número de piezas que fueron producidas "OEE": KPI de negocio para integrar "Rendimiento": porcentaje de cumplimiento de velocidad "Calidad": porcentaje de calidad "Disponiblidad": porcentaje que la máquina esta lista para producir "Downtime %": porcentaje de tiempo de inactividad "Work Order": orden de fabricación que se esta trabajando "Bad parts": Cantidad de piezas malas "Defects": Tipo de defecto y cantidad "Downtime seconds": tiempo muerto en segundos por día "Cicle time": Tiempo ciclo promedio en la última hora "Parts per hour": trabajos hechos en la última hora "Start Time": hora de inicio del úlitmo turno "Finish Time": hora de fin del úlitmo turno "Downtime Causes": Causas de tiempo muerto, en formato causa - tiempo en segundos del último turno "MTTR": Mean time to repair del último turno "MTBF": Mean time between failures del último turno

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE0Mjk3Nzc2MDksLTExMTI4OTgzNDddfQ
==
-->