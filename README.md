# CSS-animations

# Notas del curso CSS-animations

CSS animations - the complete guide with 100 projects!

=======
Demo : https://codesandbox.io/s/gallant-margulis-y7mwg?file=/README.md:1075-1148

# CSS-animations

## Transitions

# CSS animations - the complete guide with 100 projects!

- transition-property: la propiedad que va a cambiar
- transition-duration: duracion
- trasition-timing-function:Se refiere a como se producira el cambio de la propiedad, si el cambio sera constante

- transition-delay:tiempo en que la trnsicion espera antes de iniciar

## trasition-timing-function

## Transitions

Tiene cinco valores diferentes :

Demo : https://codesandbox.io/s/gallant-margulis-y7mwg?file=/README.md:1075-1148

- ease : est apor defecto ,el cambio comienza lento , en la mitad rapido ,y luegos disminuye la velocidad al final
- Liner : velocidad constante
- ease-in : inicio lento y al llegar al final rapido
- ease-out:inicio rapido y al llegar al final lento

## transition

- transition-property: la propiedad que va a cambiar
- transition-duration: duracion
- trasition-timing-function:Se refiere a como se producira el cambio de la propiedad, si el cambio sera constante
- transition-delay:tiempo en que la trnsicion espera antes de iniciar

## trasition-timing-function

=======
Se pueden añadir mas de una propiedad
ejemplo :

<pre>
  transition-property: background-color color;
  </pre>

=======
Se pueden incluir todas las propiedades con la palabra all

## Transitions

- transition-property: la propiedad que va a cambiar
- transition-duration: duracion
- trasition-timing-function:Se refiere a como se producira el cambio de la propiedad, si el cambio sera constante
- transition-delay:tiempo en que la trnsicion espera antes de iniciar

Tiene cinco valores diferentes :

<pre>
  transition-property: all;
  </pre>

Hay una propiedad abreviadas que tiene encuenta todas las propiedades de transicion llamada transition :

<pre>
transition: all 3s ease-in 2s;
</pre>

## Propiedades que no pueden ser animadas

## trasition-timing-function

PROPIEDADES QUE NO TIENE VALORES INTERMEDIOS

- Diplay
- Background-image
- Border

- FLOAT

<<<<<<< CodeSandbox

- ease : est apor defecto ,el cambio comienza lento , en la mitad rapido ,y luegos disminuye la velocidad al final
- # Liner : velocidad constante
  LISTA :https://developer.mozilla.org/es/docs/Web/CSS/CSS_Transitions/Using_CSS_transitions

* ease-in : inicio lento y al llegar al final rapido
* ease-out:inicio rapido y al llegar al final lento
  -ease-in-out

## transition

Tiene cinco valores diferentes :

- ease : est apor defecto ,el cambio comienza lento , en la mitad rapido ,y luegos disminuye la velocidad al final
- Liner : velocidad constante
- ease-in : inicio lento y al llegar al final rapido
- ease-out:inicio rapido y al llegar al final lento
  -ease-in-out

# Se pueden añadir mas de una propiedad

## transition

<pre>
  transition-property: background-color color;
=======
Se pueden añadir mas de una propiedad
ejemplo :

  </pre>

Se pueden incluir todas las propiedades con la palabra all

<pre>
  transition-property: all;
  </pre>

<pre>
  transition-property: background-color color;
  </pre>

Se pueden incluir todas las propiedades con la palabra all

Hay una propiedad abreviadas que tiene encuenta todas las propiedades de transicion llamada transition :

<pre>
transition: all 3s ease-in 2s;
</pre>

<pre>
  transition-property: all;
  </pre>

Hay una propiedad abreviadas que tiene encuenta todas las propiedades de transicion llamada transition :

## Propiedades que no pueden ser animadas

# PROPIEDADES QUE NO TIENE VALORES INTERMEDIOS

<pre>
transition: all 3s ease-in 2s;
</pre>

- Diplay
- Background-image
- # Border

## Propiedades que no pueden ser animadas

PROPIEDADES QUE NO TIENE VALORES INTERMEDIOS

- FLOAT

LISTA :https://developer.mozilla.org/es/docs/Web/CSS/CSS_Transitions/Using_CSS_transitions

# 2D Transforms

- Diplay
- Background-image
- Border
- FLOAT

Estas transformaciones incluyen rotar, torcer, escalar y desplazar

LISTA :https://developer.mozilla.org/es/docs/Web/CSS/CSS_Transitions/Using_CSS_transitions

- Translate Mueve elemntos atravez de eje x y y , traslate recibe dos valores x y y (translateX,translateY)
- Scale : Modifica el ancho
- Rotate : Rotar
- Skew: Retorcer

## transform-origin

Con la propiedad transform-origin se cambia el origen de la trasnformacion
, los valores que puede tener son :

- top
- right
- left
- top right
- bottom right
- bottom left
- top left
- asiganar valores en porcetajes o pixeles donde el primer valor es el eje x y el segundo el eje y

## Trasform -3d

Se tiene en cuenta el eje z, hay que tener en cuenta la perpectiva .

### Perpectiva

Es la dustancia entre nuestros ojos y la pantalla del computados, por lo que acepta valores en pixeles

Para crear una perpectiva se requiere

perspective
