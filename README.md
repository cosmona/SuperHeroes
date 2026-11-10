# SuperHeroes

Página de **tarjetas de superhéroes de DC Comics**: Batman, Superman y Wonder Woman. Al pasar el ratón por encima de cada tarjeta se despliega una lista de curiosidades del personaje («¿Sabías que...?»).

## Cómo verlo

Abre `index.html` en el navegador. No necesita instalar nada.

## Técnicas

- Tarjetas con imagen de fondo y transiciones CSS largas para el efecto de aparición
- Funciones `show()` y `hide()` en JavaScript, llamadas desde `onMouseOver` y `onMouseOut`, que añaden o quitan la clase `muestra`
- Diseño adaptable con `@media (min-width: 768px)`

## Estructura

```
index.html      # tarjetas y script
css/style.css
img/            # imágenes de los personajes y logo de DC
```
