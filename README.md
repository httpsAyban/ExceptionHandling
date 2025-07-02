using System;

namespace TryCatchExample
{
    class Program
    {
        static void Main(string[] args)
        {
            try
            {
                int x = 10;
                int y = 0;
                int result = x / y;
                Console.WriteLine("Result: " + result);
            }
            catch (DivideByZeroException ex)
            {
                Console.WriteLine("Error: " + ex.Message);
            }

            Console.ReadLine(); 
        }
    }
}
