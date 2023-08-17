# Glossary_WebDevelopment
Web development glossary created by the sofgrox community

# Glosario de Fundamentos Web

### Desarrollo Web:
El desarrollo web se refiere al proceso de crear y mantener sitios web o aplicaciones web. Involucra varios aspectos como el diseño, la programación, la interacción con bases de datos y la optimización para su funcionamiento en navegadores.

### Frontend:
El frontend se refiere a la parte visible de un sitio web o aplicación web con la que los usuarios interactúan directamente. Incluye el diseño, la disposición de elementos, la interacción y la presentación de información en el navegador.

### Backend:
El backend es la parte no visible de un sitio web o aplicación web. Maneja la lógica detrás de escena, la gestión de bases de datos, la autenticación de usuarios y otras funcionalidades que permiten que el frontend funcione correctamente.

### Frameworks:
Los frameworks son conjuntos de herramientas y bibliotecas predefinidas que facilitan el desarrollo web al proporcionar estructuras y patrones comunes para resolver problemas específicos. Pueden ser tanto frontend como backend.

### Librerías:
Las librerías son colecciones de funciones y código que se pueden reutilizar en el desarrollo web para realizar tareas específicas, como manejar interacciones con el DOM o gestionar peticiones HTTP.

### Base de datos:
Una base de datos es un sistema de almacenamiento estructurado que guarda y organiza datos. En el desarrollo web, se utiliza para almacenar información como usuarios, publicaciones y otros datos relevantes para la aplicación.

### Lado del cliente:
El lado del cliente se refiere a la parte de una aplicación web que se ejecuta en el navegador del usuario. Incluye el HTML, CSS y JavaScript que se encargan de la presentación y la interacción con el usuario.

### Lado del servidor:
El lado del servidor se refiere a la parte de una aplicación web que se ejecuta en el servidor. Aquí se manejan las solicitudes del cliente, se accede a la base de datos y se realiza la lógica de negocio antes de enviar la respuesta al cliente.

### Página Web:
Una página web es un documento único en un sitio web. Puede contener contenido como texto, imágenes, videos y enlaces. Las páginas web se combinan para crear un sitio web completo.

### Sitio Web:
Un sitio web es un conjunto de páginas web relacionadas que están agrupadas bajo un mismo dominio. Estas páginas pueden estar conectadas a través de enlaces y formar una experiencia cohesiva para los usuarios.

### Aplicación Web:
Una aplicación web es un tipo de software que se accede a través de un navegador web. Puede ofrecer funcionalidades avanzadas y a menudo implica interacción en tiempo real con el servidor.

### camelCase:
camelCase es una convención de escritura en la que las palabras se escriben juntas sin espacios, y cada palabra adicional después de la primera comienza con una letra mayúscula. Ejemplo: miVariableCamel.

### PascalCase:
PascalCase es una convención de escritura similar a camelCase, pero la primera letra de cada palabra también está en mayúscula. Ejemplo: MiVariablePascal.

### SNAKE_CASE:
SNAKE_CASE es una convención de escritura en la que las palabras se escriben en mayúsculas y se separan por guiones bajos. Ejemplo: MI_VARIABLE_SNAKE.

### kebab-case:
kebab-case es una convención de escritura en la que las palabras se escriben en minúsculas y se separan por guiones. Ejemplo: mi-variable-kebab.

### Visual Studio Code:
Visual Studio Code es un popular editor de código fuente desarrollado por Microsoft. Es conocido por su velocidad, capacidad de personalización y una amplia gama de extensiones.

### Plugins de Visual Studio Code:
Los plugins, también conocidos como extensiones, son complementos que se agregan a Visual Studio Code para extender sus funcionalidades. Pueden proporcionar soporte para lenguajes de programación, integración con servicios externos y más.

### Configuraciones de Visual Studio Code:
Las configuraciones son ajustes personalizables en Visual Studio Code que permiten a los desarrolladores ajustar el comportamiento del editor de acuerdo a sus preferencias. Esto incluye configuraciones de formato, resaltado de sintaxis y atajos de teclado, entre otros.


# Glosario de HTML y CSS

index.html:
El archivo index.html es el punto de entrada principal de un sitio web. Es la primera página que se carga cuando un usuario visita el sitio. Aquí se define la estructura y el contenido básico de la página web utilizando etiquetas HTML.

```
<!DOCTYPE html>:
```
La declaración '<!DOCTYPE html>' se encuentra en la parte superior de un documento HTML y especifica la versión del estándar HTML que se está utilizando. Ayuda al navegador a interpretar correctamente el contenido del documento.

```
<html></html>:
```
La etiqueta "<html>" define el inicio y el final del documento HTML. Todo el contenido de la página web se encuentra dentro de estas etiquetas.

```
<head></head>:
```
La etiqueta "<head>" contiene metadatos y enlaces a recursos externos, como hojas de estilo y scripts, que son necesarios para la presentación y el funcionamiento de la página, pero no se muestran directamente en la ventana del navegador.

```
<meta/>:
```
La etiqueta "<meta>" se utiliza para proporcionar metadatos sobre el documento HTML, como el conjunto de caracteres utilizado y la descripción de la página.

```
<meta charset="UTF-8" />:
```
La etiqueta "<meta charset="UTF-8" />" especifica que el conjunto de caracteres utilizado en la página es UTF-8, lo que permite mostrar caracteres especiales y multilingües correctamente.

```
<meta name="viewport" content="width=device-width, initial-scale=1.0" />:
```
Esta etiqueta "<meta>" con el atributo name="viewport" y el atributo content define cómo se debe ajustar el contenido de la página al ancho del dispositivo y la escala inicial.

```
<link rel="stylesheet" href="" />:
```
La etiqueta "<link>" se utiliza para vincular una hoja de estilo externa (CSS) al documento HTML, lo que permite aplicar estilos al contenido de la página.

```
<title></title>:
```
La etiqueta "<title>" se utiliza para establecer el título de la página web, que se muestra en la pestaña del navegador o en los resultados de búsqueda.

```
<body></body>:
```
La etiqueta "<body>" contiene todo el contenido visible de la página web, como texto, imágenes, enlaces y otros elementos.

```
<!-- -->:
```
El formato "<!-- comentario -->" se utiliza para insertar comentarios en el código HTML. Los comentarios no se muestran en la página y son útiles para hacer anotaciones sobre el código.

```
<h1></h1> <h2></h2> <h3></h3> <h4></h4> <h5></h5> <h6></h6>:
```
Las etiquetas "<h1> a <h6>" se utilizan para definir encabezados de diferentes niveles en la página, donde "<h1>" es el encabezado más importante y "<h6>" es el menos importante.

```
<ul></ul>:
```
La etiqueta "<ul>" se utiliza para crear una lista no ordenada, donde los elementos de la lista se presentan con viñetas.

```
<li></li>:
```
La etiqueta (<li>) se utiliza para definir elementos de lista dentro de una lista no ordenada (<ul>) o una lista ordenada (<ol>).

```
<a href=""></a>:
```
La etiqueta "<a>" se utiliza para crear enlaces o hipervínculos a otras páginas web o recursos. El atributo href especifica la dirección URL de destino.

ruta relativa (patch):
Una ruta relativa se refiere a la ubicación de un archivo o recurso en relación con el archivo HTML actual. Se utiliza, por ejemplo, en enlaces o referencias a otros archivos.

"./"+:
La notación "./" se utiliza en rutas relativas para indicar la ubicación actual del archivo. Puede ser parte de una ruta para navegar a carpetas en el mismo directorio.

CSS:
CSS (Cascading Style Sheets) es un lenguaje de diseño utilizado para controlar la presentación y el aspecto visual de un documento HTML. Permite definir estilos como colores, fuentes, márgenes y más.

class="":
El atributo class se utiliza para asignar una o varias clases a un elemento HTML. Las clases se utilizan en CSS para aplicar estilos específicos a esos elementos.

id="":
El atributo id se utiliza para identificar de manera única un elemento HTML. Puede usarse para aplicar estilos específicos o para realizar manipulaciones con JavaScript.

```
<script src=""></script>:
```
La etiqueta "<script>" se utiliza para agregar scripts o código JavaScript a una página HTML. El atributo src especifica la ruta del archivo de script externo que se debe cargar.

# Glosario de JavaScript

console.log():
console.log() es una función de JavaScript que se utiliza para imprimir mensajes en la consola del navegador o en la consola de desarrollo. Es útil para depurar y visualizar valores de variables.

alert():
alert() es una función de JavaScript que muestra un mensaje emergente en una ventana del navegador. Se utiliza para proporcionar información al usuario de manera inmediata.

var:
var fue una palabra clave en JavaScript utilizada para declarar variables antes de las versiones más modernas de ECMAScript (ES6). Ahora se recomienda el uso de let y const.

let:
let es una palabra clave en JavaScript que se utiliza para declarar variables de ámbito local. Las variables declaradas con let pueden cambiar de valor después de su declaración.

const:
const es una palabra clave en JavaScript que se utiliza para declarar variables cuyo valor no cambiará después de su asignación inicial. Las variables declaradas con const son de solo lectura.

concatenar:
Concatenar es el proceso de unir cadenas de texto para formar una cadena más larga. En JavaScript, se puede lograr usando el operador + para combinar cadenas.

scope de variable:
El scope de una variable se refiere a la parte del código donde la variable es accesible y tiene valor. Puede ser global (accesible desde cualquier parte del código) o local (accesible solo dentro de un bloque o función específicos).

String:
String es un tipo de dato en JavaScript que representa una secuencia de caracteres. Puede contener letras, números y símbolos.

int:
int es una abreviatura de "integer", que se refiere a números enteros (números sin decimales) en JavaScript.

float:
float es un tipo de dato en JavaScript que se refiere a números con decimales, también conocidos como números de punto flotante.

boolean:
boolean es un tipo de dato en JavaScript que solo puede tener dos valores: true (verdadero) o false (falso). Se utiliza para expresar estados lógicos.

prompt():
prompt() es una función de JavaScript que muestra un cuadro de diálogo en el navegador, permitiendo que el usuario ingrese datos. El valor ingresado se puede asignar a una variable.

function:
function es una palabra clave en JavaScript que se utiliza para definir una función, que es un bloque de código reutilizable que puede recibir argumentos, realizar tareas y devolver un valor.

\n:
\n es un carácter de escape que se utiliza en cadenas de texto para representar un salto de línea, lo que hace que el texto siguiente aparezca en una nueva línea.

toLowerCase():
toLowerCase() es un método de cadena en JavaScript que convierte todos los caracteres de una cadena a minúsculas.

toUpperCase():
toUpperCase() es un método de cadena en JavaScript que convierte todos los caracteres de una cadena a mayúsculas.

if/else:
if/else es una estructura de control en JavaScript que se utiliza para tomar decisiones condicionales en el código. Si se cumple una condición, se ejecuta el bloque if, de lo contrario, se ejecuta el bloque else.

if anidado:
Los if anidados son múltiples bloques if colocados dentro de otros bloques if o else. Se utilizan para manejar varias condiciones y acciones en función de diferentes casos.

else if:
else if es una extensión de la estructura if/else que permite verificar múltiples condiciones alternativas antes de recurrir al bloque else.

Operadores de comparación:
Los operadores de comparación se utilizan para comparar valores en JavaScript y devuelven un valor booleano (true o false) según si la comparación es verdadera o falsa.

==: Igual a.
===: Estrictamente igual a.
>: Mayor que.
<: Menor que.
>=: Mayor o igual que.
<=: Menor o igual que.
!=: Diferente de.
!==: Estrictamente diferente de.
Operadores lógicos:
Los operadores lógicos se utilizan para combinar o invertir valores booleanos en JavaScript.

&&: Operador AND lógico (Y).
||: Operador OR lógico (O).
null:
null es un valor especial en JavaScript que representa la ausencia intencionada de cualquier valor o referencia a un objeto.

undefined:
undefined es un valor que indica que una variable no tiene un valor asignado. Si una variable se declara pero no se inicializa, su valor será undefined.

vacio "":
Una cadena vacía ("") es una cadena que no contiene ningún carácter. Es diferente de null y undefined, ya que es un valor válido de cadena en JavaScript.
