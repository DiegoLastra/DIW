# CSS
## CSS etiqueta para aplicar el box-sizing a toda la pagina.
Para aplicarlo a toda la pagina se utiliza este codigo *Incluye los pseudocodigos:*
```
*, *::before,::after,*:before,*:after{
    box-sizing: border-box;
}
```
Para aplicar el estilo a toda la pagina sin incluir los pseudocodigos se utilza:
```
*,{
    box-sizing: border-box;
}
```