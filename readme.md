# Semana 4

## Estilos de Texto 

### 1. Font-Family
#### Modifica la familia tipografica.
#### Ejemplo: 
#### h1{}. 


### 2. Font-size
#### Modifica el tamaño de fuente.
#### Ejemplo:
#### font-size: xx-large. 


### 3. Line-Height
#### Interlineado entre las filas. 
#### Ejemplo: 
#### line-height: 100px;


### 4. Text-Align
#### Permite centrar, izquierda, derecha el texto.
#### Ejemplo:
#### text-align: center;

### 5. Font-Weight
#### Peso del texto.
#### Ejemplo:
#### font-weight: 900;


### 6. Font-Weight
#### Underline texto. 
#### Ejemplo: 
#### text-decoration: underline;  



## Selectores

### 1. Selector de Etiqueta
#### Los selectores de etiqueta son aquellos que permiten aplicar estilos a todas las etiquetas de un tipo.
#### Ejemplo: 
#### Sintaxis: h1{ propiedades de estilo }, h2{ propiedades de estilo }, p{ propiedades de estilo };  


### 2. Selector de Clase
#### Los selectores de clase buscan un elemento basado en el contenido de su atributo class.
#### Ejemplo: 
#### Sintaxis: .nombre de clase { propiedades de estilo }


### 3. Selector ID
#### Un selector de ID está diseñado para seleccionar elementos con base en su atributo de ID.
#### Ejemplo: 
#### Sintaxis:  #nombre de ID { propiedades de estilo }


### 4. Selector Descendencia
#### El selector descendiente es el elemento que es descendiente de otro elemento.
#### Ejemplo: 
#### Sintaxis:  selector1 selector2 { propiedades de estilos }


### 5. Selector Hijo Directo
#### Es usado para aplicar los estilos a los hijos directos de un elemento. Puede estar hecho por dos o más selectores que estan separados con el signo mayor que (>).
#### Se puede usar este selector para seleccionar el primer nivel de los elementos anidados.
#### Ejemplo: 
#### Sintaxis:  ul>li { propiedades de estilos }


### 6. Selector Hermano Siguiente o Adyacente
#### Este selector puede ser usado para seleccionar los elementos hermanos (los que estan al mismo nivel). Su sintaxis es un elemento seguido del signo más (+)
#### y luego el otro elemento, donde el objetivo a aplicarle los estilos es el segundo elemento.
#### Ejemplo: 
#### Sintaxis:  h1+ p { propiedades de estilos }


### 7. Selector Hermanos Siguientes o Adyacentes
#### ‌Es parecido al adyacente pero no es tan estricto. Se pueden seleccionar dos selectores separados por una virgulilla (~).
#### Se puede tener un elemento separado por la virgulilla, seguido del otro elemento, y el objetivo del selector para aplicar los estilos es el segundo. Ambos elementos #### deben tener el mismo padre. 
#### Ejemplo: 
#### Sintaxis:  h1 ~ p { propiedades de estilos }


### 8. Selector de Anidamiento
#### Permitir escribir unos selectores dentro de otros junto con sus propiedades y valores. 
#### Ejemplo: 
#### Sintaxis:  .section.h1 span.a{ propiedades de estilos }


