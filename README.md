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

###  index.html:
El archivo index.html es el punto de entrada principal de un sitio web. Es la primera página que se carga cuando un usuario visita el sitio. Aquí se define la estructura y el contenido básico de la página web utilizando etiquetas HTML.

```
<!DOCTYPE html>:
```
La declaración !DOCTYPE html se encuentra en la parte superior de un documento HTML y especifica la versión del estándar HTML que se está utilizando. Ayuda al navegador a interpretar correctamente el contenido del documento.

```
<html></html>:
```
La etiqueta html define el inicio y el final del documento HTML. Todo el contenido de la página web se encuentra dentro de estas etiquetas.

```
<head></head>:
```
La etiqueta head contiene metadatos y enlaces a recursos externos, como hojas de estilo y scripts, que son necesarios para la presentación y el funcionamiento de la página, pero no se muestran directamente en la ventana del navegador.

```
<meta/>:
```
La etiqueta meta se utiliza para proporcionar metadatos sobre el documento HTML, como el conjunto de caracteres utilizado y la descripción de la página.

```
<meta charset="UTF-8" />:
```
La etiqueta meta charset="UTF-8"  especifica que el conjunto de caracteres utilizado en la página es UTF-8, lo que permite mostrar caracteres especiales y multilingües correctamente.

```
<meta name="viewport" content="width=device-width, initial-scale=1.0" />:
```
Esta etiqueta meta con el atributo name="viewport" y el atributo content define cómo se debe ajustar el contenido de la página al ancho del dispositivo y la escala inicial.

```
<link rel="stylesheet" href="" />:
```
La etiqueta link se utiliza para vincular una hoja de estilo externa (CSS) al documento HTML, lo que permite aplicar estilos al contenido de la página.

```
<title></title>:
```
La etiqueta title se utiliza para establecer el título de la página web, que se muestra en la pestaña del navegador o en los resultados de búsqueda.

```
<body></body>:
```
La etiqueta body contiene todo el contenido visible de la página web, como texto, imágenes, enlaces y otros elementos.

```
<!-- -->:
```
El formato !-- comentario -- se utiliza para insertar comentarios en el código HTML. Los comentarios no se muestran en la página y son útiles para hacer anotaciones sobre el código.

```
<h1></h1> <h2></h2> <h3></h3> <h4></h4> <h5></h5> <h6></h6>:
```
Las etiquetas h1 a h6 se utilizan para definir encabezados de diferentes niveles en la página, donde h1 es el encabezado más importante y h6 es el menos importante.

```
<ul></ul>:
```
La etiqueta ul se utiliza para crear una lista no ordenada, donde los elementos de la lista se presentan con viñetas.

```
<li></li>:
```
La etiqueta li se utiliza para definir elementos de lista dentro de una lista no ordenada ul o una lista ordenada ol.

```
<a href=""></a>:
```
La etiqueta a se utiliza para crear enlaces o hipervínculos a otras páginas web o recursos. El atributo href especifica la dirección URL de destino.

### ruta relativa (patch):
Una ruta relativa se refiere a la ubicación de un archivo o recurso en relación con el archivo HTML actual. Se utiliza, por ejemplo, en enlaces o referencias a otros archivos.

### "./"+:
La notación "./" se utiliza en rutas relativas para indicar la ubicación actual del archivo. Puede ser parte de una ruta para navegar a carpetas en el mismo directorio.

### CSS:
CSS (Cascading Style Sheets) es un lenguaje de diseño utilizado para controlar la presentación y el aspecto visual de un documento HTML. Permite definir estilos como colores, fuentes, márgenes y más.

### class="":
El atributo class se utiliza para asignar una o varias clases a un elemento HTML. Las clases se utilizan en CSS para aplicar estilos específicos a esos elementos.

### id="":
El atributo id se utiliza para identificar de manera única un elemento HTML. Puede usarse para aplicar estilos específicos o para realizar manipulaciones con JavaScript.

### color: #2f2fb9;
Esta regla establece el color del texto dentro del elemento HTML al valor "#2f2fb9". El valor "#2f2fb9" representa un tono de azul en formato hexadecimal.

### font-size: 50px;
Esta regla define el tamaño de la fuente del texto dentro del elemento HTML como "50px" (píxeles). Esto determina cuán grande será el texto visualmente en relación con el resto del contenido.

### text-decoration: none;
Esta regla elimina cualquier decoración de texto, como subrayados, de un enlace (elemento <a>). Cuando se establece en "none", el enlace no mostrará ninguna línea adicional debajo del texto.

```
<script src=""></script>:
```
La etiqueta script se utiliza para agregar scripts o código JavaScript a una página HTML. El atributo src especifica la ruta del archivo de script externo que se debe cargar.

# Glosario de JavaScript

### console.log(): Es una función que muestra mensajes en la consola del navegador o en la consola de desarrollador. Se utiliza para depurar y mostrar información durante el desarrollo de una aplicación.
Es como tener una pequeña ventana donde puedes escribir cosas para que la computadora te las muestre. Es como hablarle a la computadora para que te diga algo.

### alert(): Es una función que muestra una ventana emergente en el navegador con un mensaje y un botón "Aceptar". Se utiliza para mostrar información importante o mensajes de advertencia al usuario.
Es como una cajita que aparece en la pantalla y muestra un mensaje importante. Es como cuando alguien te dice "¡Mira esto!".

### var: Antiguamente se usaba para declarar variables en JavaScript, pero ahora se recomienda usar let y const debido a problemas con el ámbito (scope) y la forma en que las variables var pueden ser izadas (hoisting).
Es como una caja donde puedes guardar cosas. Pero a veces es un poco confuso, así que no lo usamos mucho.

### let: Es una palabra clave que se utiliza para declarar variables con ámbito de bloque. Las variables declaradas con let tienen un alcance limitado al bloque en el que se declaran.
Es como una caja que puedes cambiar de vez en cuando. Puedes poner cosas diferentes en ella cuando quieras.

### const: Es una palabra clave que se utiliza para declarar constantes. Las variables declaradas con const no pueden cambiar su valor después de la asignación inicial y también tienen un ámbito de bloque.
Es como una caja fuerte que pones una cosa y no la cambias nunca. Lo que pongas ahí se queda igual.

### concatenar: Es la acción de combinar cadenas de texto. En JavaScript, puedes concatenar cadenas utilizando el operador +.
Es cuando pegas dos cosas juntas, como unir piezas de lego para hacer algo más grande.

### scope de variable: Se refiere a la visibilidad y accesibilidad de una variable en diferentes partes del código. Las variables pueden tener ámbito global (visibles en todo el código) o ámbito local (visibles solo en ciertas partes del código).
Imagina que cada caja que usas solo puede verse en ciertas partes de tu habitación. No todas las cajas pueden ser vistas desde cualquier lugar.

### Hoisting es un término extraño, pero en realidad es bastante simple de entender. Imagina que tienes una habitación y en esa habitación tienes muchas cajas. Cada caja contiene algo diferente, como juguetes, libros o ropa. Ahora, cuando entras a la habitación, primero miras todas las cajas y anotas en un papel lo que hay en cada una antes de empezar a jugar o usar las cosas.

En JavaScript, algo similar sucede con las declaraciones de variables y funciones. Antes de que el código se ejecute, JavaScript "levanta" (hoists) todas las declaraciones de variables y funciones al principio de su ámbito (como una función o un archivo). Esto significa que, aunque puedas haber escrito el código en un orden específico, JavaScript reorganiza internamente estas declaraciones antes de ejecutarlo.

Hoisting es un comportamiento en JavaScript donde las declaraciones de variables y funciones se mueven automáticamente al comienzo de su alcance antes de que se ejecute el código. Aunque en realidad no se mueven físicamente en el código, este comportamiento puede llevar a resultados sorprendentes si no se comprende correctamente.

El hoisting se aplica principalmente a las declaraciones de variables y funciones, pero no a las asignaciones de variables. Aquí tienes algunos ejemplos para ilustrar este concepto:

### String: Es un tipo de dato que representa una secuencia de caracteres, como texto. Se puede crear utilizando comillas simples o dobles: 'texto' o "texto".

### int: No existe un tipo de dato específico llamado "int" en JavaScript. Los números enteros son representados por el tipo de dato numérico y pueden contener tanto enteros como decimales.

### float: Tampoco existe un tipo de dato llamado "float" en JavaScript. Los números con decimales se representan mediante el tipo de dato numérico.

### boolean: Es un tipo de dato que representa un valor de verdad, es decir, puede ser true (verdadero) o false (falso). Se utiliza para expresar condiciones y tomar decisiones en el código.

### prompt(): Es una función que muestra una ventana emergente en el navegador con un campo de entrada de texto y botones "Aceptar" y "Cancelar". Se utiliza para obtener entrada del usuario.

### function: Es un bloque de código reutilizable que puede aceptar argumentos y devolver un resultado. Las funciones son fundamentales en la programación para organizar y modular el código.

### onclick="": Es un atributo HTML utilizado para asignar una función de JavaScript que se ejecutará cuando un elemento, como un botón, sea clicado.

### \n: Es un carácter de escape que representa una nueva línea en una cadena de texto. Se utiliza para dar formato al texto.

### toLowerCase(), toLocalLowerCase(), toUpperCase(), toLocalUpperCase(): Son métodos de las cadenas de texto que se utilizan para cambiar el caso de las letras en una cadena. toLowerCase() convierte a minúsculas, toLocalLowerCase() lo hace considerando la configuración regional del sistema, toUpperCase() convierte a mayúsculas y toLocalUpperCase() lo hace considerando la configuración regional.

### if/else: Son estructuras de control que se utilizan para tomar decisiones en el código. El bloque if ejecuta un conjunto de instrucciones si se cumple una condición, y el bloque else ejecuta un conjunto de instrucciones si la condición no se cumple.

### if anidado: Es cuando tienes una estructura if dentro de otra estructura if. Esto permite evaluar múltiples condiciones de manera secuencial.

### else if: Es una extensión de la estructura if que se utiliza para evaluar condiciones adicionales en caso de que la condición anterior no se cumpla.

### Operadores de comparación: Son símbolos que se utilizan para comparar valores. Algunos ejemplos son == (igualdad), === (igualdad estricta), > (mayor que), < (menor que), >= (mayor o igual que), <= (menor o igual que), != (diferente), !== (diferente estricto).

### Operadores lógicos: Son utilizados para combinar condiciones y realizar operaciones lógicas. && representa el operador "y" lógico, mientras que || representa el operador "o" lógico.

### null: Es un valor especial que representa la ausencia intencional de cualquier objeto o valor.

### undefined: Es un valor que indica que una variable no ha sido asignada o declarada.

### vacio "": Se refiere a una cadena de texto sin caracteres, es decir, una cadena con longitud cero.

### NaN: Significa "Not-a-Number" (No es un número). Se devuelve cuando se realiza una operación matemática inválida.

### parseFloat: Es una función que convierte una cadena en un número de punto flotante (decimal).

### parseInt: Es una función que convierte una cadena en un número entero.

### isNaN(): Es una función que devuelve true si el valor proporcionado no es un número válido, de lo contrario devuelve false.

### Condicional switch: Es una estructura de control utilizada para realizar múltiples comparaciones y ejecutar diferentes bloques de código según el valor de una expresión.

### case y break;: Son utilizados en una estructura switch para definir diferentes casos y las acciones a realizar cuando se cumple cada caso. break se utiliza para salir del bloque switch después de que se ha ejecutado un caso.

### DOM: El Document Object Model (Modelo de Objetos del Documento) es una representación en memoria de la estructura de un documento HTML. Permite a los scripts acceder y manipular elementos HTML y sus propiedades.

### document (DOM): Es el objeto global que representa el documento HTML en JavaScript. Proporciona métodos y propiedades para interactuar con los elementos del documento.

### getElementById (DOM): Es un método que busca y devuelve un elemento del DOM según su atributo id.

### getElementsByName (DOM): Es un método que devuelve una lista de elementos del DOM que tienen un atributo name específico.

### getElementsByClassName (DOM): Es un método que devuelve una lista de elementos del DOM que tienen una clase específica asignada css. Puedes acceder a estos elementos y manipularlos utilizando JavaScript.

### getElementsByTagName (DOM): Es un método que devuelve una lista de elementos del DOM que tienen una etiqueta HTML específica, como <div>, <p>, <a>, etc.

### getElementsByTagNameNS (DOM): Similar al método getElementsByTagName, pero utilizado para elementos con un espacio de nombres específico en documentos XML o SVG.

innerHTML (DOM): Es una propiedad de los elementos del DOM que permite acceder o modificar el contenido HTML interno de un elemento. Ten en cuenta que cambiar innerHTML puede tener implicaciones de seguridad y rendimiento.
