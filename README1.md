// Dado del 1 al 6
using System;
public class Juego01c
{
    public static void Main()
    {
        int miliseg = DateTime.Now.Millisecond; int dado = miliseg % 6 + 1;
        Console.Write("El numero del dado es "); Console.WriteLine(dado);
    }
}
