# actividad-
using System;
 
namespace ejercicio_basicos_DDR_2
{
    class MainClass
    {
        public static void Main (string[] args)
        {
 
            Console.WriteLine (&quot;Escribe tu nombre&quot;);
            String nombre = Console.ReadLine ();
 
            Console.WriteLine (&quot;Escribe una ciudad&quot;);
            String ciudad = Console.ReadLine ();
 
            Console.WriteLine (&quot;Hola &quot; + nombre + &quot; bienvenido a &quot;+ciudad);

 
            Console.ReadLine ();
 
        }
    }
} 
