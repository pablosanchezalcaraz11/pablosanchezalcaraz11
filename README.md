using System;

namespace PresentacionPersonal
{
    class Program
    {
        static void Main(string[] args)
        {
            string nombre = "Pablo";
            string apellidos = "Sánchez";
            string ciudad = "Alicante";
            string estudios = "Estadística";

            Console.WriteLine("Presentación Personal:");
            Console.WriteLine("-----------------------");
            Console.WriteLine($"Nombre: {nombre} {apellidos}");
            Console.WriteLine($"Ciudad de origen: {ciudad}");
            Console.WriteLine($"Estudios: {estudios}");

            Console.WriteLine("\nPulsa cualquier tecla para salir...");
            Console.ReadKey();
        }
    }
}
