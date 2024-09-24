## Tipos primitivos Java
Los tipos primitivos son aquellos que solo guardan un tipo de dato simple y se almacenan directamente en la memoria.

<table>
    <thead>
        <th>Tipo</th>
        <th>Valor</th>
        <th>Tamaño (bits)</th>
    </thead>
    <tbody>
        <tr>
            <td>boolean</td>
            <td>true, false</td>
            <td align="center">1</td>
        </tr>
        <tr>
            <td>char</td>
            <td>Carácter Unicode</td>
            <td align="center">16</td>
        </tr>
        <tr>
            <td>byte</td>
            <td>Entero (+, -)</td>
            <td align="center">8</td>
        </tr>
        <tr>
            <td>short</td>
            <td>Entero (+, -)</td>
            <td align="center">16</td>
        </tr>
        <tr>
            <td>int</td>
            <td>Entero (+, -)</td>
            <td align="center">32</td>
        </tr>
        <tr>
            <td>long</td>
            <td>Entero (+, -)</td>
            <td align="center">64</td>
        </tr>
        <tr>
            <td>float</td>
            <td>Decimal (+, -)</td>
            <td align="center">32</td>
        </tr>
        <tr>
            <td>double</td>
            <td>Decimal (+, -)</td>
            <td align="center">64</td>
        </tr>
    </tbody>
</table>

También existen clases complejas o _wrappers_ para algunos:
- Boolean
- Character
- Integer
- Long
- Float
- Double

## Declaración de variables
Las variables pueden ser de cualquier tipo primitivo mencionado anteriormente, de sus clases complejas (wrappers), de clases propias de Java o de clases creadas por nosotros (objetos).

Por ejemplo:
- int n = 0;
- Integer n = 0;
- String frase = "Hello world!";
- Scanner scanner = new Scanner(System.in);
- Persona persona = new Persona(18, "John Doe");

## Operadores
Los operadores son símbolos reservador a relizar operaciones aritméticas o de comparación.

<table>
    <thead>
        <th>Operador</th>
        <th>Descripción</th>
        <th>Ejemplo de uso</th>
        <th>Resultado</th>
    </thead>
    <tbody>
        <tr>
            <td>+</td>
            <td>Suma</td>
            <td align="center">2 + 1</td>
            <td align="center">3</td>
        </tr>
        <tr>
            <td>-</td>
            <td>Resta</td>
            <td align="center">2 - 1</td>
            <td align="center">1</td>
        </tr>
        <tr>
            <td>*</td>
            <td>Multiplica</td>
            <td align="center">2 * 2</td>
            <td align="center">4</td>
        </tr>
        <tr>
            <td>/</td>
            <td>Divide</td>
            <td align="center">12 / 2</td>
            <td align="center">6</td>
        </tr>
        <tr>
            <td>%</td>
            <td>Residuo</td>
            <td align="center">12 % 2</td>
            <td align="center">0</td>
        </tr>
        <tr>
            <td>++</td>
            <td>Incrementa el valor en uno</td>
            <td align="center">1++</td>
            <td align="center">2</td>
        </tr>
        <tr>
            <td>--</td>
            <td>Decrementa el valor en uno</td>
            <td align="center">2--</td>
            <td align="center">1</td>
        </tr>
        <tr>
            <td>+=</td>
            <td>Suma combinada</td>
            <td align="center">a += b</td>
            <td align="center">a = a + b</td>
        </tr>
        <tr>
            <td>-=</td>
            <td>Resta combinada</td>
            <td align="center">a -= b</td>
            <td align="center">a = a - b</td>
        </tr>
        <tr>
            <td>*=</td>
            <td>Multiplicación combinada</td>
            <td align="center">a *= b</td>
            <td align="center">a = a * b</td>
        </tr>
        <tr>
            <td>/=</td>
            <td>División combinada</td>
            <td align="center">a /= b</td>
            <td align="center">a = a / b</td>
        </tr>
        <tr>
            <td>%=</td>
            <td>Residuo combinado</td>
            <td align="center">a %= b</td>
            <td align="center">a = a % b</td>
        </tr>
        <tr>
            <td>==</td>
            <td>Igual que</td>
            <td align="center">7 == 8</td>
            <td align="center">false</td>
        </tr>
        <tr>
            <td>!=</td>
            <td>Diferente que</td>
            <td align="center">7 != 8</td>
            <td align="center">true</td>
        </tr>
        <tr>
            <td><</td>
            <td>Menor que</td>
            <td align="center">7 < 8</td>
            <td align="center">true</td>
        </tr>
        <tr>
            <td><</td>
            <td>Mayor que</td>
            <td align="center">7 > 8</td>
            <td align="center">false</td>
        </tr>
        <tr>
            <td><=</td>
            <td>Menor o igual que</td>
            <td align="center">7 <= 8</td>
            <td align="center">true</td>
        </tr>
        <tr>
            <td>>=</td>
            <td>Mayor o igual que</td>
            <td align="center">7 >= 8</td>
            <td align="center">false</td>
        </tr>
        <tr>
            <td>!</td>
            <td>Negación (NOT)</td>
            <td align="center">!false</td>
            <td align="center">true</td>
        </tr>
        <tr>
            <td>|</td>
            <td>Suma inclusiva</td>
            <td align="center">true | false</td>
            <td align="center">true</td>
        </tr>
        <tr>
            <td>^</td>
            <td>Suma lógica exclusiva (XOR)</td>
            <td align="center">true ^ false</td>
            <td align="center">true</td>
        </tr>
        <tr>
            <td>&</td>
            <td>Producto inclusivo</td>
            <td align="center">true & false</td>
            <td align="center">false</td>
        </tr>
        <tr>
            <td>||</td>
            <td>Suma lógica exclusiva (OR)</td>
            <td align="center">true || false</td>
            <td align="center">true</td>
        </tr>
        <tr>
            <td>&&</td>
            <td>Producto lógico exclusivo (AND)</td>
            <td align="center">false && true</td>
            <td align="center">false</td>
        </tr>
    </tbody>
</table>

## Clase String
La clase String pertenece a Java y **NO** es un tipo primitivo. Se puede comparar a un array de _char_. Esta clase siempre se construye usando comillas dobles("). Para introducir ciertos carácteres hace falta escribirlos de una manera especial.

<table>
    <thead>
        <th>Carácter de escape</th>
        <th>Valor</th>
    </thead>
    <tbody>
        <tr>
            <td>\b</td>
            <td>Restroceso (no se suele usar)</td>
        </tr>
        <tr>
            <td>\t</td>
            <td>Tabulación</td>
        </tr>
        <tr>
            <td>\n</td>
            <td>Nueva línea</td>
        </tr>
        <tr>
            <td>\f</td>
            <td>Avance de línea (no se suele usar)</td>
        </tr>
        <tr>
            <td>\r</td>
            <td>Retorno (no se suele usar)</td>
        </tr>
        <tr>
            <td>\"</td>
            <td>Comillas dobles</td>
        </tr>
        <tr>
            <td>\'</td>
            <td>Comillas simples</td>
        </tr>
        <tr>
            <td>\\</td>
            <td>Backslash</td>
        </tr>
        <tr>
            <td>\uxxxx</td>
            <td>Carácter unicode correspondiente al valor de xxxx</td>
        </tr>
    </tbody>
</table>

## Bifurcaciones
Las bifurcaciones se usan para ejecutar ciertas partes del código basandose en el resultado booleano de una comparación. Existen estos tres tipos:

### if-else
La bifurcación if-else es la más común. Se usa una declaración _if_, se puede acompañar de tantas declaraciones _if else_ como sea necesario y se termina con una declaración _else_.

```
if (expresión booleana) { // Declaración obligatoria única
    
    bloque de código;

} else if (expresión booleana) { // Declaración opcional única o múltiple

    bloque de código;

} else { // Declaración opcional única

    bloque de código;

};
```

### switch-case
La bifurcación switch-case es muy parecida a la if-else pero puede resultar más útil en ciertos casos. De manera similar, se usa una declaración _switch_, se puede acompañar de tantas declaraciones _case_ como sea necesario, y se termina con una declaración _default_.

```
switch (expresión booleana) { // Declaración obligatoria única
    case x: // Declaración opcional única o múltiple
        bloque de código;
    break; // Indicar que el caso acaba aquí

    default: // Declaración opcional única
        
        bloque de código;
};
```

### Operador ternario
El operador ternario es una simplificación de la bifurcación if-else para poder escribir sentencias con dos casos posibles de forma rápida. Se usa una condición seguida de una interrogación (?) y luego dos valores separados por dos puntos (:). El primer valor será asignado en caso que la condición sea _true_ y el segundo valor será asignado en caso que la condición sea _false_.

```
tipo nombreVariable = (condición) ? valor1 : valor2;
```

## Bucles
Los bucles se usan para ejecutar bloques de código repetidamente. Existen estos cuatro tipos:

### for
El bucle for es el más común. Se usa para repetir un bloque de código un número de veces definido. En su declaración encontramos tres elementos, una variable (normalmente i de iterador), una expresión booleana y una operación con la variable i (normalmente de incremento).

```
// Cada iteración del bucle ejecutará el bloque de código e incrementará la variable i (int i = 0) en uno (i++). Esto sucederá hasta que la expresión booleana sea falsa, en este caso cuando la variable i sea mayor que 10 (i < 10).

for (int i = 0; i < 10; i++) {

    bloque de código;

};

```

### for-each
El bucle for-each es una variación del bucle for. Se introdujo porque son muchas las ocasiones en las que hay que recorrer arrays o listas. En su declaración encontramos dos elementos, una variable con el mismo tipo del array o lista y la referencia al propio array o lista.

```
// Cada iteración ejecutará el bloque de código, que normalmente realizará una operación con el elemento actual del array o lista al que tenemos acceso gracias a la primera variable (int n). Esto sucederá hasta que se hayan recorrido todos los elementos del array o lista, en este caso hay 100 elementos (int[] numeros = new int[100]).

int[] numeros = new int[100];
for (int n : numeros) {

    bloque de código;

};

```

### while

### do-while
