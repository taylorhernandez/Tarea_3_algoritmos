
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
namespace Main
{
    class año
    {
        static void Main(string[] args)
        {
            int a;
            Console.WriteLine("Ingresa año");
            a = Convert.ToInt32(Console.ReadLine());
            if (a % 4 == 0 && (a % 100 != 0 || a % 400 == 0))
            {
                Console.WriteLine("El año " + a + " Si es bisiesto ");
            }
            else
            {
                Console.WriteLine("El año " + a + " No es bisiesto ");
            }
            Console.ReadLine();
        }
    }
}
