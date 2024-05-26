# CSS Grid

```html

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="src/style.css">
  </head>
  <body>
    
   <div class="container">
        <div class="item">item</div>
        <div class="item">item</div>
        <div class="item">item</div>
        <div class="item">item</div>
        <div class="item">item</div>
        <div class="item">item</div>
        <div class="item">item</div>
        <div class="item">item</div>
    </div>

  </body>
</html>
```

```css
*{
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}


.container{
  background-color: gray;
  width: 460px;
  height: 360px;
  display: grid;
  grid-template-columns:1fr 1fr 1fr 1fr  ;
  grid-template-rows: 60px 60px 60px;
  gap: 20px;
}

.item {
  width: 100%;
  height: 100%;
  background-color: blue;
}
```



## Actividad: Creación de una galería de fotos

1. Traer la fuente Roboto de https://fonts.google.com/

Seleccionar la fuente y hacer clic en "embed code"

copiar las siguientes lineas de html

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&display=swap" rel="stylesheet">
```
Y agregarlas dentro de la etiqueta `<head>`

ir al `src/style.css`
```css
html, body{
  font-family: "Roboto", sans-serif;
}
```

2. Colocar nuestras variables de CSS

```css
:root{
  --primary-color: #212121;
  --text-color: #607D8B;  
}

html, body{
  font-family: "Roboto", sans-serif;
  color: var(--text-color); 
}
```




