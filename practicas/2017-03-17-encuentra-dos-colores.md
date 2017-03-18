# Descripción
Dado un color X y un listado de colores, encuentra dos colores dentro del listado que al mezclarse den el color X.

La función en éste caso se llamará **findColorMatches** y debe retornar un arreglo con los dos colores encontrados.

Por [@reneolivo](https://github.com/reneolivo).

### Listado de colores

```javascript
var colors = [
  { red: 90, green: 80, blue: 30 },
  { red: 20, green: 120, blue: 40 },
  { red: 30, green: 80, blue: 200 },
  { red: 200, green:150, blue: 80 },
  { red: 70, green: 220, blue: 90 },
  { red: 90, green: 100, blue: 20 },
  { red: 40, green: 30, blue: 50 },
  { red: 120, green: 70, blue: 30 },
];
```

### Ejemplo:

```javascript
var color1 = { red: 30, green: 75, blue: 45 };
result = findColorMatches(color1);
console.log(result); // [ { red: 20, green: 120, blue: 40 }, { red: 40, green: 30, blue: 50 } ];
```

:goberserk::goberserk::goberserk: [Codepen con pruebas de ejemplo](http://codepen.io/Chakstor/pen/oZpWgE?editors=0010)
