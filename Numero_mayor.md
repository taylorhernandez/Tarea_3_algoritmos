
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
namespace comparar_tres_numeros
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Ingrese un numero");
         int A = Convert.ToInt16(Console.ReadLine());
            Console.WriteLine("Ingrese un numero");
         int B = Convert.ToInt16(Console.ReadLine());
            Console.WriteLine("Ingrese un numero");
         int C = Convert.ToInt16(Console.ReadLine());
            if(A > B && A > C)
        {
        Console.WriteLine("El numero mayor es "+A);
        }
        else
        {
            if(B > A && B > C)
            {
            Console.WriteLine("El numero mayor es "+B);
            }
            else
            {
            Console.WriteLine("El numero mayor es "+C);
            }            
        }
            Console.ReadLine();
        }
    }
}
