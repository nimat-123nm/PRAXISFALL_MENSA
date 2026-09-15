# PRAXISFALL_MENSA

namespace LS5___Algorithmus_und_EVA_in_C_
{
    internal class Program
    {
        static void Main(string[] args)
        {
            

            Console.Write("Artikelname: ");
            string artikelname = Console.ReadLine();

            Console.Write("Einzelpreis (CHF): ");
            decimal einzelpreis = decimal.Parse(Console.ReadLine());

            Console.Write("Menge: ");
            int menge = int.Parse(Console.ReadLine());

            decimal gesamtpreis = einzelpreis * menge;

           
            
            Console.WriteLine($"Artikel:      {artikelname}");
            Console.WriteLine($"Einzelpreis:  CHF {einzelpreis:F2}");
            Console.WriteLine($"Menge:        {menge}");
            Console.WriteLine($"Gesamtpreis:  CHF {gesamtpreis:F2}");



        }
    }
}
