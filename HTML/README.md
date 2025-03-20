# HTML 
### HyperText Markup Language

Permite describir la estructura de los archivos web.

> **NOTA:** se utiliza _"index.html"_ debido a que en la antigüedad por defecto, todas las páginas de la web buscaban el archivo de entrada index.

### Etiquetas y Elementos
![Diferencia entre Etiqueta y Elemento HTML](./images/HTML1.png)

#### Tipos de etiquetas

##### Títulos
```
<h1>Título 1</h1>
<h2>Título 2</h2>
<h3>Título 3</h3>
<h4>Título 4</h4>
<h5>Título 5</h5>
<h6>Título 6</h6>
```

##### Párrafos
```
<p>Párrafo</p>
```

#### Etiquetas anidadas
```
<p>
Párrafo
<strong>negrita</strong>
</p>
```

##### Listas desordenadas
```
<ul>
  <li>Elemento de lista</li>
  <li>Elemento de lista</li>
  <li>Elemento de lista</li>
</ul>
```

#### Etiquetas reemplazables

Estos elementos son reemplazados por un tipo de contenido en específico, en el siguiente caso, multimedia.
```
<img src="./images/avatar.jpg" alt="Avatar RickErazo" />
```

Otro tipo es ```<input >```

### Atributos
Proporcionan información adicional a los elementos HTML. Existen dos tipos de atributos:
- **Globales:** se pueden utilizar en cualquier etiqueta HTML. Por ejemplo: _class, id, style, etc._
  * _**id:**_ es un atributo el cual identifica al elemento HTML como único dentro del proyecto, motivo por el cual debe ser exclusivo y no repetirse.
  * _**class:**_ es la identificación que se le puede dar a uno o varios elementos que posean el mismo comportamiento o se repitan.
- **Específicos:** ayuda a identificar al tipo de la etiqueta necesaria. Por ejemplo: _src, alt, etc._

![Ejemplos de Atributos de etiquetas](./images/HTML2.png)

> **NOTA:** se recomienda utilizar en las etiquetas letras minúsculas siempre.

HTML no requiere los estilos.

> **NOTA:** la representación de los elementos en HTML se da debido a los _user agent stylesheet_ que tienen por defecto cada navegador.