
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
namespace MayorTresNumeros
{
    class Estatura
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Ingrese tú altura");
            int A = Convert.ToInt16(Console.ReadLine());

        
            if (A >= 0 && A <= 130)
            {
                Console.WriteLine("Resultado esperado");
                Console.WriteLine("Tu estatura es  muy baja ");
            }
            else
            {
             
                if (A>=131 && A<=150)
                {
                    Console.WriteLine("Resultado esperado");
                    Console.WriteLine("Tu estatura es mediana");
                }
                else
                {
                    Console.WriteLine("Resultado esperado");
                    Console.WriteLine("Tu estatura es alta ");
                }
            }
            Console.ReadLine();
        }
    }
}
