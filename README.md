<p>
  using System;

class Program
{
    static void Main()
    {
        // Declaración y creación de arreglos para almacenar los datos de la canción
        string[] artista = new string[1];
        string[] titulo = new string[1];
        int[] duracion = new int[1];
        int[] tamano = new int[1];

        // Solicitar y almacenar los datos de la canción
        for (int i = 0; i < 1; i++)
        {
            Console.WriteLine("Ingrese los datos de la canción: ");

            Console.Write("Artista: ");
            artista[i] = Console.ReadLine();

            Console.Write("Título: ");
            titulo[i] = Console.ReadLine();

            Console.Write("Duración (en segundos): ");
            duracion[i] = int.Parse(Console.ReadLine());

            Console.Write("Tamaño del fichero (en KB): ");
            tamano[i] = int.Parse(Console.ReadLine());
        }

        // Mostrar los datos de la canción
        Console.WriteLine("\nDatos de la canción ingresada:");
        for (int i = 0; i < 1; i++)
        {
            Console.WriteLine($"Artista: {artista[i]}");
            Console.WriteLine($"Título: {titulo[i]}");
            Console.WriteLine($"Duración (segundos): {duracion[i]}");
            Console.WriteLine($"Tamaño del fichero (KB): {tamano[i]}\n");
        }
    }
}
</p>
