


# Servicios de Consulta de los datos

En la siguiente página se muestran los servicios a los cuales se pueden acceder para consultar la información de **Monitor**

## Unidades Trabajadas `GET`
El siguiente servicio se puede consultar la cantidad de Unidades trabajadas de las _Estaciones_

**Path**
`GET /api/dashboard`

**Params**
```js
{
	date: 'YYYY-MM-DD HH:mm:ss'
}
```
Es necesario enviar la fecha que se requiere consulta (consulta por del día). Es necesario enviar la *fecha* y *hora* ya que se toma en cuenta la hora para saber con exactitud el *horario* de la consulta. Los casos en los que se presenta esto son en horarios nocturnos en días posteriores. Ejemplo

```js
{
	date: '2023-02-02 01:20:00'
}
```
**Response**
```json
{
  "items":  [
    {
      "workstation":  "Estacion 1",
      "alias":  "Alias de Estacion",
      "date":  "2023-02-01",
      "schedule":  "17:00-03:00"
      "part":{
        "name":  "parte 1",
        "alias":  "Alias de Parte 1",
        "count":  "200.0"
	   },
      "date":  "2023-02-01",
	  "schedule":  "17:00-03:00"
	}
  ]
}
```


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEwNzU3MTU5MTYsMTAzMDYxMjMzOV19
-->