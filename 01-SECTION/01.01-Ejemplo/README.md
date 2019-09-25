# Section 01: Ejemplo 01
## Cambios en el css
Al añadir en el css el:
```
div{
    box-sizing: border-box;
    }
```
el width y el height no van a ser modificados por futuros bordes
o padding añadidos en el div
```
div{
    box-sizing: border-box;
    width: 20rem;
    height: 20rem;
    background-color: salmon;
    padding: 5rem;
    border: 20px  solid blue;
}
```
Si el texto se que hemos añadido se sale de las dimensiones
establecidas podemos añadir un:
```
div{
    overflow: auto;
}
```
que añade una barra en el recuadro que permite bajar y subir para poder leer todo el texto añadido