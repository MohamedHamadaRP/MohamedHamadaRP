using System;

namespace perfect_numpers
{
    class Program
    {
        
        static void Main()
        {
             //i can not to print the perfect numpers once it would be rebeted un tell loop ends
             
            Console.WriteLine("the frist num must be >1\n");
            Console.WriteLine("please inter frist num ");
            int n1 = int.Parse(Console.ReadLine());
            Console.WriteLine(" inter scond num ");
            int n2 = int.Parse(Console.ReadLine());
            Console.WriteLine( "\n");
            for(int k=n1; k<n2; k++)
            {
                int h = 0;
                
                for (int i = 1; i < k; i++)
                {

                    if (k % i == 0)
                        h += i;

                    else if (k == h)
                    { Console.WriteLine(k); }
                    
                    
                }
            }
            
        }
    }
}
