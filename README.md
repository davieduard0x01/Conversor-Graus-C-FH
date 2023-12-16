using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp17
{  class Graus
    {   public  double conversor(double convers)
        {
            double grauc = convers;
            double Fahr = grauc * (9.0 / 5.00) + 32.00;
            return Fahr;


        }

    }
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Digite o valor em Graus Celsios para ser convertido ");
            double graus=double.Parse(Console.ReadLine());
            Graus grs = new Graus();
            double result;
            result = grs.conversor(graus);
            Console.WriteLine(result);
            Console.ReadKey();
        }
    }
}
//F = C * (9.0 / 5.0) + 32.0, sendo F a temperatura em
//Fahrenheit e C a temperatura em Celsius.
// DAVIEDUARD0X01 
