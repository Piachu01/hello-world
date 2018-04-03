# hello-world\

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace kalkulator_stary
{
    class Program
    {
        static void Main(string[] args)
        {
            
            Console.WriteLine("Podaj pierwszą liczbę :");
            int pierwsza = int.Parse(Console.ReadLine());
            Console.WriteLine("Podaj drugą liczbę:");
            int druga = int.Parse(Console.ReadLine());
            Console.WriteLine("Jakie działanie chcesz wykonać?\n1 - Dodawanie\n2 - Odejmowanmie\n3 - Mnożenie\n4 - Dzielenie");
            string wybór = Console.ReadLine();

            if (wybór == "1")
            {
                Console.WriteLine("Suma tych liczb to:");
            }
            Console.ReadLine();
        }

    }
}

