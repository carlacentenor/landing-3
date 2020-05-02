# Landing Wave
----------------------------

:smile: En mi camino de seguir mejorando mis skills he realizado esta linda landing siguiendo el tutorial de  
 [AlexCG Design](https://www.youtube.com/watch?v=HH_SMpxV7qQ) en youtube.


 >  :exclamation:Siempre es importante reconocer a sus maestros 

## :bulb: Aprendizaje del día : 

### Header con efecto 

Descubri que existia esta propiedad

`background-attachment: fixed; `
 
Esta propiedad me permite realizar el efecto de scrool a la imagen. 

La imagen de fondo estará fija en la pantalla y no se moverá con el bloque contenedor.

![Con titulo](https://user-images.githubusercontent.com/32285482/80853216-78038880-8bf4-11ea-8062-51ed588f4620.gif "Header")

### Wave

La figura wave ( ola) que se muestra en el header fue creado con SVG .
Existe un recurso para generar estas figuras y se encuentra en este link :
[Generador de Wave](https://smooth.ie/blogs/news/svg-wavey-transitions-between-sections)

Aquí encontraras herramientas para crear de manera rápida y fácil y además te da el código html. !Es una maravilla!


~~~
  <div class="wave" style="height: 150px; overflow: hidden;"><svg viewBox="0 0 500 150" preserveAspectRatio="none" style="height: 100%; width: 100%;"><path d="M0.00,49.99 C287.25,161.94 349.20,-49.99 500.00,49.99 L500.00,150.00 L0.00,150.00 Z" style="stroke: none; fill: #fff;"></path></svg></div>
 ~~~

 ![Con titulo](https://user-images.githubusercontent.com/32285482/80853319-6d95be80-8bf5-11ea-97f3-0eb4ea911b00.PNG "Web")

### Efecto Hover 

He realizado en mi camino de front efectos hover diferentes, pero este cuando lo vi pense que tenia algo de javascript y me asombro aprender que fue solo con css.

Utilizando  transform y transition pueden salir cosas asombrosas. Asi que a jugar con esas propiedades y comencemos a experimentar.

~~~
.hover-gallery {
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    transform: scale(0);
    background: rgba(131, 96, 195, 0.774);
    transition: transform .5s;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
}

.img-port:hover .hover-gallery {
    transform: scale(1);
}
~~~
![Con titulo](https://user-images.githubusercontent.com/32285482/80853415-61f6c780-8bf6-11ea-9b4d-bc9b92a32a9b.gif "hover")


Ha sido muy interesante seguir este tutorial y aprender más cosas. 
Seguire en mi camino de mejorar cada día mis skills y enseñando lo que voy aprendiendo.

:star:"Porque el que enseña aprende dos veces":star:

### Landing
![Con titulo](https://user-images.githubusercontent.com/32285482/80852839-6b316580-8bf1-11ea-94a8-d9851bc687c0.png "Web")
