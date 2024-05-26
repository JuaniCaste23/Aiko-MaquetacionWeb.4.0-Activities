# Clase 5

Alinear elementos con display: block, inline e inline-block

```html
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <Link rel="stylesheet" type="text/css" href="src/style.css" />
</head>

<body>

  <div class="container">
    <div class="element-1">element-1</div>
    <div class="elemento-2">element-2</div>
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

body{
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100wv;
  height: 100hv;
}

/*apuntar a contaainer y darle 400 px de ancho y 200 px de alto y darle un color de fondo*/

.container {
  width: 410px;
  height: 200px;
  background-color: rgb(241, 137, 0);
  border-radius: 12px;
}


/* apuntar a alemento-1 y darle ancho de 200px y alto de 200px  y un color de fonto red*/

.element-1 {
  width: 200px;
  height: 200px;
  background-color: red;
  display: inline-block;

}

/* apuntar al elemento-2 y darle  ancho de 200px y alto de 200px  y un color de fondo blue */

.elemento-2 {
  width: 200px;
  height: 200px ;
  background-color: blue;
  display: inline-block;
}

```
