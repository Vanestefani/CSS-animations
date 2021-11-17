# CSS-animations

CSS animations - the complete guide with 100 projects!

Demo : https://codesandbox.io/s/gallant-margulis-y7mwg?file=/README.md:1075-1148

## Transitions

- transition-property: la propiedad que va a cambiar
- transition-duration: duracion
- trasition-timing-function:Se refiere a como se producira el cambio de la propiedad, si el cambio sera constante
- transition-delay:tiempo en que la trnsicion espera antes de iniciar

## trasition-timing-function

Tiene cinco valores diferentes :

- ease : est apor defecto ,el cambio comienza lento , en la mitad rapido ,y luegos disminuye la velocidad al final
- Liner : velocidad constante
- ease-in : inicio lento y al llegar al final rapido
- ease-out:inicio rapido y al llegar al final lento
  -ease-in-out

## transition

Se pueden añadir mas de una propiedad
ejemplo :

<pre>
  transition-property: background-color color;
  </pre>

Se pueden incluir todas las propiedades con la palabra all

<pre>
  transition-property: all;
  </pre>

Hay una propiedad abreviadas que tiene encuenta todas las propiedades de transicion llamada transition :

<pre>
transition: all 3s ease-in 2s;
</pre>

## Propiedades que no pueden ser animadas

PROPIEDADES QUE NO TIENE VALORES INTERMEDIOS

- Diplay
- Background-image
- Border
- FLOAT

LISTA :https://developer.mozilla.org/es/docs/Web/CSS/CSS_Transitions/Using_CSS_transitions
