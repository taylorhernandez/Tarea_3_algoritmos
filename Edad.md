using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;

class edad_para_votar
{
    static void Main(string[] args)
    {

        Console.WriteLine("Escribe tú edad");
        int a = Convert.ToInt16(Console.ReadLine());
        if (a >= 21)
        {
            Console.WriteLine("Resultado esperado:");
            Console.WriteLine( "Felicidades usted puede votar");
        }
        else
        {
            Console.WriteLine("Resultado esperado:");
            Console.WriteLine("Usted no tiene la edad suficiente para votar");
        }
        Console.ReadLine();
    }

}

