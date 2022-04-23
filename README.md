# MSalert
*Es necesario importar Jquery para su funcionamiento*
## Alertas Principales
```javascript
MSalert.principal(
	{
		icon: 'warning',
		title: 'titulo',
		description: 'descripcion',
		button: false, // false por defecto
		extra:'extra data despues de descripcion', // no es necesario
	}
)
```
### Tipos de iconos
- warning
- success
- error

> si el button es true se creara un boton de si y no, se devolvera en valor clickeado en una promesa

## Alertas de campos
```javascript
MSalert.alerta(
	{
		id:'body', // id del div, input 
		text : 'Requeridos', // texto de la alerta
		position: 'right', // posición de la alerta
		status: "success", // estado "color"
		duration: 3000, // duración de la alerta antes de desaparecer
	}
)
```
### Tipos de status
- success
- warning
- error

### Tipos de posiciones
- down
- up
- right
