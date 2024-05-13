# Frontend Mentor - Interactive card details form

![Design preview for the Interactive card details form coding challenge](./design/desktop-preview.jpg)

## Reto

[URL del challenge](https://www.frontendmentor.io/challenges/interactive-rating-component-koxpeBUmI)
[Demo de la app](https://interactive-card-details-form-main-zeta.vercel.app/)

Os adjunto la demo para que veaís fácilmente como funciona la app. No inspeccioneis el código, ni siquiera por que hay _algo_ que no os sale. Prefiero que me llaméis a mi.

1. Escribir con lenguaje natural una idea de lo que tiene que ocurrir en esta aplicación. Podéis escribirlo en el mismo README.md más abajo
2. En principio todo el CSS necesario y maquetación ya está implementado. Pero puedes añadir tus clases CSS, estilos en línea a partir de la propiedad .style, etc.
3. Primero, no tengáis en cuenta ninguna validación. Simplemente, haced que la información que escribís en el formulario, aparezca donde pertoque en la tarjeta
4. Hay varias estrategias para validar los campos del formulario. TAmbién para limitar el número de carácteres. Exploradlas por vuestra cuenta y podéis tomar de referencia como está hecho en la solución, **PERO no tiene porque ser exactamente igual**. Sed críticos y pensad cuál es el problema a resolver en esta aplicación.
5. Todo el formulario está dentro de una etiqueta _form_ , que es un tanto especial. Si no estáis familiarizados con event.preventDefault(), consultadmelo.
6. Bonus! Puedes hacer que al seleccionar un valor, se quede marcado en naranja.

## Pregunta 1: Describe con lenguaje natural que tiene que hacer la app.
- Al rellenar todos los campos y quitarles el foco, los cambios quedan reflejados en el lado izquierdo de la app;
- Al hacer click al boton Confirm - poner display:none al formulario, - poner display:block al Thank you div, 
- Añadir atributo required en los campos del formulario
- Añadir mensajes de error si se hace click al botón Confirm, pero los campos no están rellenados
- Dar el formato correcto y limitar el número de los dígitos de la tarjeta (max 16)
- Limitar el CVC a tres dígitos 