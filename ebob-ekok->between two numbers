using System;

namespace ConsoleApp2
{
    class Program
    {
        static void Main(string[] args)
        {
            while (true)
            {
                int number1, number2;
                int ebob = 1;
                Console.WriteLine("Pozitif 1. tam sayi giriniz:");
                bool x = int.TryParse(Console.ReadLine(), out number1);
                Console.WriteLine("Pozitif 2. tam sayi giriniz:");
                bool y = int.TryParse(Console.ReadLine(), out number2);
                if (x == false || y == false || number1 <= 0 || number2 <= 0)
                    Console.WriteLine("Dogal sayi degil\n ");
                else
                {
                    int temp = number1;
                    if (number1 > number2)
                        temp = number2;
                    for (int i = 2; i <= temp; i++)
                    {
                        if (number1 % i == 0 && number2 % i == 0)
                            ebob = i;
                    }
                    Console.WriteLine("EBOB : " + ebob);
                    Console.WriteLine("EKOK : " + (number1 * number2) / ebob);
                    Console.ReadLine();
                }
            }
        }
    }
}
