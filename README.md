using System;
class Program
{
    static void Main()
    {
        //надоело вызвать ошибку УЖЕЕЕ
        int n1 = int.Parse("123");
        Console.WriteLine(n1);
        if (int.TryParse("456", out int n2))
            Console.WriteLine(n2);
        DateTime date1 = DateTime.ParseExact("25.12.2023", "dd.MM.yyyy", null);
        Console.WriteLine(date1.ToString("yyyy-MM-dd"));
        if (DateTime.TryParseExact("2023-12-25", "yyyy-MM-dd", null,
            System.Globalization.DateTimeStyles.None, out DateTime date2))
            Console.WriteLine(date2.ToString("dd.MM.yyyy"));
    }
}
//ГОСПОДИ ЧТО ЭТО 
//Я УСТАЛ ХОЧУ ПОЕСТЬ И СПАТЬ 
