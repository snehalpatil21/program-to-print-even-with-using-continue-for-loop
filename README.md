# program-to-print-even-with-using-continue-for-loop
Using System;
Using System.IO;
Using System.Linq;
Using System.Collections.Generic;

Namespace CSharp_Shell
{

    Public class Program 
    {
        Public static void Main()
        {
			Int I;
			For(i=1;i<=10;i++)
            {
              If(i%2==0)
              {
              	If((i>=6)&&(i<=10))
              	{
              		Console.WriteLine(i);
              		Continue;
              	}
              }
            }
            Console.ReadLine();
        }
        
    }
}
