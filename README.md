# Reto en Java: comprobación de mayoría de edad

## Datos del grupo

- **Integrantes:** [escribir aquí los nombres de los integrantes]
- **Lenguaje asignado:** Java
- **Reto asignado:** comprobar si una persona es mayor o menor de edad mediante una condición.

## Descripción

En `reto.java` hemos creado un programa que guarda una edad y comprueba si es mayor o igual que 18. Si se cumple la condición, muestra `Mayor de edad`; en caso contrario, muestra `Menor de edad`.

## Investigación y comparación

### 1. ¿Cómo se declara la variable o el contador?

En Java hay que indicar el tipo de dato al declarar una variable. En nuestro ejemplo usamos:

```java
int edad = 20;
```

`int` indica que la variable contiene un número entero. En Python no es necesario escribir el tipo:

```python
edad = 20
```

### 2. ¿Cómo se muestra información por consola?

En Java utilizamos `System.out.println()`:

```java
System.out.println("Mayor de edad");
```

En Python utilizaríamos `print()`.

### 3. ¿Cómo se delimitan los bloques de código?

Java delimita los bloques mediante llaves `{ }`. Además, normalmente termina cada instrucción con punto y coma `;`.

Python no utiliza llaves para estos bloques: usa los dos puntos `:` y la indentación. En ambos lenguajes la indentación ayuda a leer el código, pero en Python también determina qué instrucciones pertenecen a cada bloque.

### 4. ¿Qué símbolos o palabras cambian respecto al ejemplo en Python?

- Java declara el tipo de la variable con `int`; Python no lo necesita.
- Java encierra la condición entre paréntesis: `if (edad >= 18)`.
- Java utiliza llaves `{ }`; Python utiliza `:` e indentación.
- Java usa `else` seguido de un bloque entre llaves; Python usa `else:`.
- Java suele terminar las instrucciones con `;`; Python no.
- Java muestra texto con `System.out.println()`; Python utiliza `print()`.

El operador de comparación `>=` y las palabras `if` y `else` se mantienen en ambos lenguajes.

### 5. ¿Qué decisiones o repeticiones se mantienen?

El programa toma la misma decisión en Java que en Python: compara la edad con 18. Si la edad es igual o superior a 18, informa de que la persona es mayor de edad. Si es inferior, informa de que es menor de edad. No se utiliza ninguna repetición o bucle en este reto.

Algoritmo explicado sin código:

1. Guardar la edad de la persona.
2. Comparar la edad con 18.
3. Si la edad es igual o superior a 18, mostrar que es mayor de edad.
4. En caso contrario, mostrar que es menor de edad.

### 6. ¿Se necesita algún elemento adicional para ejecutar el programa?

Sí. Java necesita una clase y un método principal desde el que comienza la ejecución:

```java
public class reto {
    public static void main(String[] args) {
        // Aquí se encuentra el programa.
    }
}
```

La clase y el método `main` son necesarios para ejecutar este ejemplo, pero no forman parte de la estructura condicional `if-else` que estamos investigando. En un script sencillo de Python no es obligatorio crear una clase ni una función principal.

## Código y resultado

El código entregado se encuentra en `reto.java`. Con el valor actual, `edad = 20`, muestra:

```text
Mayor de edad
```

## Cómo compilar y ejecutar

Es necesario tener instalado el JDK de Java. Desde la carpeta del proyecto:

```text
javac reto.java
java reto
```

## Puesta en común

- **Funcionamiento de la condición:** `if` comprueba si la edad es mayor o igual que 18. `else` se ejecuta cuando esa condición es falsa.
- **Semejanza con Python:** los dos lenguajes utilizan `if` y `else` para decidir qué mensaje mostrar.
- **Diferencia con Python:** Java requiere indicar el tipo de la variable y delimitar los bloques con llaves, mientras que Python utiliza la indentación.

### Pregunta final

Lo aprendido en Python nos ha servido para entender la lógica del algoritmo: guardar un dato, compararlo mediante una condición y elegir uno de dos resultados. Al pasar el ejercicio a Java, la lógica se mantiene y lo que cambia principalmente es la sintaxis.
