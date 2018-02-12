# FactorialJavayPython
El factorial de un número es la multiplicación de los número que van del 1 a dicho número

Codigo java
package calculofactorial;
public class CalculoFactorial {
 // declaración recursiva del método factorial
 public long factorial( long numero )
 {
 if ( numero <= 1 ) // evalúa el caso base
 return 1; // casos base: 0! = 1 y 1! = 1
 else // paso recursivo
 return numero * factorial( numero - 1 );
} // fin del método factorial

 // imprime factoriales para los valores del 0 al 10
 public void mostrarFactoriales()
 {
 // calcula los factoriales del 0 al 10
 for ( int contador = 0; contador <= 16; contador++ )
 System.out.printf( "%d! = %d\n", contador, factorial( contador ) );
 } // fin del método mostrarFactoriales
 } // fin de la clase CalculoFactorial

Metodo 

package calculofactorial;
public class PruebaFactorial {
// calcula los factoriales del 0 al 10
 public static void main( String args[] )
 {
 CalculoFactorial calculoFactorial = new CalculoFactorial();
 calculoFactorial.mostrarFactoriales();
 } // fin del método main
 } // fin de la clase PruebaFactorial





Codigo python



Codigo Phyton Factorial 

1)
print(6 * 5 * 4 * 3 * 2 * 1)

2)
from math import factorial
factorial(5)

3)
def factorial(x,n):
 if(n>0):
  x=factorial(x,n-1)
  x=x*n
 else:
  x=1
 return x
n=int(input("ingresa un numero  \n"))
x=1
x=factorial(x,n)
print (x)





