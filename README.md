# Taller-POO
Talleres POO
//SEGUNDA SESION 
using System;
using System.Collections.Generic;
using System.Linq;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace POOTaller
{
    internal static class Program
    {
        /// <summary>
        /// Punto de entrada principal para la aplicación.
        /// </summary>
        [STAThread]
        static void Main()
        {
            string nombre;
            Console.WriteLine("digita tu nombre");
            Console.ForegroundColor = ConsoleColor.Red;
            nombre  = Console.ReadLine();
            Console.WriteLine("Su nombre es :" + nombre + ❤️);

        }
    }
    // FIN SEGUNDA SESION 
    
// INICIO SESION 4 
// Create a Main class
public class Main {
 
  // Create a fullThrottle() method
  public void fullThrottle() {
    System.out.println("El coche va tan rapido como puede!");
  }

  // Create a speed() method and add a parameter
  public void speed(int velocidadMax) {
    System.out.println("La velocidad maxima es : " + velocidadMax + "km");
  }

  // Inside main, call the methods on the myCar object
  public static void main(String[] args) {
    Main miCoche = new Main();     // Create a myCar object
    miCoche.fullThrottle();      // Call the fullThrottle() method
    miCoche.speed(200);          // Call the speed() method
    
  }
}
// EJERCICIO 2 
public class Main {

  public void fullThrottle() {
    System.out.println("The car is going as fast as it can!");
  }

  public void speed(int maxSpeed) {
    System.out.println("Max speed is: " + maxSpeed);
  }
  public void startAndGo() {
    System.out.println(" INICIANDO LA MARCHA ADELANTE:");
    System.out.println("1. Se pisa el Clutch (Embrague) completamente.");
    System.out.println("2. Se selecciona la Primera marcha.");
    System.out.println("3. Se suelta el freno de mano.");
    System.out.println("4. Se suelta el Clutch despacio y simultáneamente se acelera poco a poco.");
    System.out.println("¡El coche ha comenzado a moverse!");
  }

  public void goReverse() {
    System.out.println("\n (REVERSA):");
    System.out.println("1. Se frena y el coche se detiene.");
    System.out.println("2. Se pisa el  Clutch (Embrague) completamente.");
    System.out.println("3. Se selecciona Neutro.");
    System.out.println("4. Se selecciona la marcha de Reversa.");
    System.out.println("5. Se comprueba el entorno y se suelta el Clutch despacio mientras se acelera suavemente.");
    System.out.println("¡El coche se está moviendo hacia atrás!");
  }
}
// 2 PARTE 
class CarSimulator {
  public static void main(String[] args) {
    Main myCar = new Main(); 
    myCar.startAndGo(); 
    myCar.speed(40);
    myCar.goReverse();
  }
}
// FIN SESION 4 
