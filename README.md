# ExerciciosURI
Exercicio uri 1117 resoluÇão !

using System;
using System.Security.Cryptography.X509Certificates;
using System.Globalization;

namespace estrututura_condicional_exercicio
{    //Exercício de lógica uri 1117
    class Program
    {
        static void Main(string[] args)
        {

            double nota2, nota1 = double.Parse(Console.ReadLine(), CultureInfo.InvariantCulture);

            while (nota1 < 0.0 || nota1 > 10)
            {

                Console.WriteLine("nota invalida");
                nota1 = double.Parse(Console.ReadLine(), CultureInfo.InvariantCulture);

            }
              
            
                  nota2 = double.Parse(Console.ReadLine(), CultureInfo.InvariantCulture);
            
            
            while (nota2 < 0.0 || nota2 > 10.0)
            {
                 Console.WriteLine("nota invalida");
                 nota2=double.Parse(Console.ReadLine(),CultureInfo.InvariantCulture);

            }

                   double media = (nota1 + nota2) / 2.0;

                Console.WriteLine("media = " + media.ToString("F2"), CultureInfo.InvariantCulture);
            
             
           

            
           

                
















        }








    }














}


