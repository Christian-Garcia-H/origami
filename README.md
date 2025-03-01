## Origami es una libreria de CSS  1/03/24
esta libreria es de facil uso para hacer paginas en minutos
## utilidades de esta libreria:
### colores
#### colores de background
##### colores primarios de background
bg-green -> color verde
bg-red -> color rojo
bg-blue -> color azul
##### colores neutros de background
bg-grey -> color gris
bg-white -> color blanco
bg-black -> color negro
##### otros colores de background
bg-yellow -> color amarillo
#### colores de fuente
##### colores primarios de fuente
c-green -> color verde
c-red -> color rojo
c-blue -> color azul
##### colores neutros de fuente
c-grey -> color gris
c-white -> color blanco
c-black -> color negro
##### otros colores de fuente
c-yellow -> color amarillo
#### colores customizados
en esta libreria se puede adjuntar un archivo css con la 
siguiente sintaxis:
>:root {
    --one: #004b23; 
    --two: #006400;
    --three: #007200;
    --four: #008000;
    --five: #38b000;
    --six: #70e000;
    --seven: #9ef01a;
    --eight: #ccff33;
}

despues puedes usar cada uno de los colores con:
bg-one -> en este caso seria el color ``--one: #004b23; ``

### width y height
#### width en px
w-200
w-300
w-400
w-auto
#### height en px
h-50
h-100
h-200
h-auto


## valores por defecto
margin ``0`` y uso de box model en todo el documento html,
algunas etiquetas tienen valores por defecto como color, altura, ancho,padding y margin para que una pagina pueda tener una opcion inicial de estilos
> header
este elemento tiene un ``width`` auto, el height minimo es de ``30px``, tiene un ``padding`` por defecto  de ``10px`` sin ``margin`` y un color #d00000ff 
