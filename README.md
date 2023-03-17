# repoprueba

hola mundo

function suma(x, y) {
  // "x" e "y" son números
  // Suma "x" e "y" juntos y devuelve el valor
  // Tu código:
  
  return x+y;

  estoy aprendiendo hacer un commit jajajaajajajajajajaja

return false o true es booleano

me paro en la carpeta que cree 
luego code .
abre el visual studio editar el repositorio
luego git add .
luego git commit -m "mensaje en comillas"
luego git push 
surgen los cambios en el repo de git hub


public class HolaMundo {
    public static void main(String[] args) {
        System.out.println("¡Hola, mundo!");
    }
}

Este código define una clase llamada HolaMundo que contiene un método llamado main. El método main es el punto de entrada del programa, es decir, donde comienza la ejecución.

Dentro del método main, utilizamos el objeto System.out para imprimir por pantalla el mensaje "¡Hola, mundo!" utilizando el método println.


public static void main(String[] args) {
   // ta bravo eh
}

Este código es la estructura básica de cualquier programa Java. Define un método llamado "main" que es el punto de entrada de cualquier programa Java. El argumento "String[] args" es una matriz de cadenas que contiene cualquier argumento que se pase al programa al iniciarlo.

Dentro del método "main" es donde se escribe el código específico del programa, por lo que se utiliza para iniciar cualquier tarea o proceso que el programa deba realizar. Por ejemplo, se puede utilizar para imprimir mensajes en la consola, solicitar entrada del usuario, realizar cálculos matemáticos, entre otras tareas.

Este código es esencial para cualquier programador de Java, ya que sin él no se puede ejecutar ningún programa Java.



import java.util.Scanner;

public class SumaResta {
    public static void main(String[] args) {
        Scanner input = new Scanner(System.in);
        
        System.out.print("8: ");
        int num1 = input.nextInt();
        
        System.out.print("9: ");
        int num2 = input.nextInt();
        
        int suma = num1 + num2;
        int resta = num1 - num2;
        
        System.out.println("La suma de los números es: " + suma);
        System.out.println("La resta de los números es: " + resta);
        
        input.close();
    }
}

Este programa primero importa la clase Scanner para poder leer la entrada del usuario. Luego, pide al usuario que ingrese dos números enteros y los guarda en las variables num1 y num2. A continuación, realiza la suma y resta de los números y los guarda en las variables suma y resta. Por último, imprime los resultados en la consola utilizando la función System.out.println().