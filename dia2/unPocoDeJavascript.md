# Un poco de java Script 

- Antes de comenzar necesitamos un editor de texto puedes usar notepad o textedit pero yo recomiendo que descarguen [Visual Studio Code](https://code.visualstudio.com/download).
 - Puedes encontrar más información [aqui](https://www.w3schools.com/js/default.asp).

** ¿Que es Java Script?

Java Script es un lenguaje de programación en el que se pueden implementar funciones más complejas para las páginas web. 
Java Script puede actualizar tanto HTML como CSS, y por esto se puede observar como la tercera capa de un pastel de Web 

<p align="center">
    <img src="https://github.com/nataly-8h/patrones-hermosos-web-course/blob/master/dia2/webcake.jpg">
</p>

-	HTML define el contenido de las paginas web
-	CSS especifica el diseño de las paginas
-	Java Script es el comportamiento de las paginas web


** Variables 

Los tipos de datos más comunes en java script son:
 - Números 
    ```javascript
    var x = 17;    
    var x1 = 17.56;
    ```
 - Strings
    ```javascript
    var nombre = “Verónica”; //String
    var nombre2 = ‘Verónica’; // String
    var nombre3 = 'Dice que se llama “Verónica” '; //String con comillas dentro
    ```
 - Objetos
    ```javascript
    var a = {edad: 18, nombre: ‘Verónica’}; 
    ```
 - Arreglos
    ```javascript
    var sabores = [“Chocolate”, “Fresa”, “Vainilla”];  //Arreglo de strings
    var sonAceptados = [true, false, false, false]; 
    ```
 - Funciones
    ```javascript
    function ejemplo(a, b){
        return a + b; 
    }
    ```
 - Booleanos
    ```javascript
    var y = true; 
    ```

** Hola Mundo
Hola mundo usando Javascript
1. Abre Visual Studio Code
2. Crea una carpeta donde quieras guardar este ejemplo
3. Crea el archivo index.html
    En este archivo pon lo siguiente:
    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Patrones Hermosos</title>  <!--El título del documento -->
    </head>
    <body>
    </body>
    </html>
    ```
4. Crea un archivo hola.js
En este archivo pon lo siguiente: 
    ```javascript
    document.write("<h1> Hola mundo :) </h1>");
    ```
5. En el <body> de index.html pon la siguiente línea
    ```html
    <script src="hola.js"></script> <!—referencia a archivo js-->
    ```
    Esta línea se encarga de hacer referencia al archivo .js
    
6.  Listo! Ya tienes un “Hola mundo” utilizando Java Script. Puedes provarlo abriendo el archivo html desde tu explorador de archivos 

** Console log
Console log muestra un mensaje desde la consola web. La puedes ver desde inspector en la página, puedes abrirlo el menú de Web Developer con ctrl + shift + I (Windows) o cmd + option + C (Mac OS): 

```javascript
console.log("Hola desde consola");
```
Mostraría
```Hola desde consola```

O si escribes 
```javascript
console.log([1,4,5]);
```
Mostraría
```▶ Array [1,4,5]```
Si selecciones en la flechita se despliegan los elementos del arreglo, así como su posición
```
▼(3) [...]
    0: 1
    1: 4
    2: 5
    length: 2
 ▶<prototype>: Array []
```

Si tienes un objeto
```javascript
var a = {edad: 18, nombre: 'Verónica'}; 
console.log(a.edad);
```
Mostraría ```18```, ya que se está refiriendo a la propiedad edad.
Puedes hacer lo mismo de la siguiente manera:
```javascript
var a = {"edad": 18, "nombre": 'Verónica'}; 
console.log(a["edad"]);
```

