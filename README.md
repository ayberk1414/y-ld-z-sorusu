# y-ld-z-sorusu
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp10
{
    class Program
    {


        static void Main(string[] args)
        {
            Console.WriteLine("lutfen bir satir sayi giriniz");
            int kullanıcıdanalincidanalinandeger = Convert.ToInt32(Console.ReadLine());
            for (int i = kullanıcıdanalincidanalinandeger; i > 0; i--)
            {
                for (int j = i; j > 0; j--)
                {
                    Console.Write("*");
                }
                Console.WriteLine();
            }
            for (int k = 1; k <= kullanıcıdanalincidanalinandeger; k++)
            {
                for (int m = 0; m < k; m++)
                {
                    Console.Write("*");
                }
                Console.WriteLine();
                Console.ReadLine();
            }

        }
    }
}
