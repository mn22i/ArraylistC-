# ArraylistC-





     internal class Program
    {
        static void Main(string[] args)
        {
            ArrayList arr = new ArrayList();
            arr.Add("Java");
            arr.Add("python");
            arr.Add("HTMLs");
            arr.Add("C#");
            arr.Add("C++");
            foreach (object obj in arr)
                Console.WriteLine(obj);

            arr.Insert(2, "Amani");
            Console.WriteLine("The item after insert is:");
            foreach (object obj in arr)
                Console.WriteLine(obj);


            arr.RemoveAt(3);
            Console.WriteLine("The item after remove is:");
            foreach (object obj in arr)
                Console.WriteLine(obj);

            arr.Sort();
            Console.WriteLine("The item after sort is:");
            foreach (object obj in arr)
                Console.WriteLine(obj);

            Console.WriteLine("The item after contains is:"+arr.Contains("programmingIII"));
           
            arr.Reverse();
            Console.WriteLine("The item after revers is:");
            foreach (object obj in arr)
                Console.WriteLine(obj);
            Console.ReadLine();
        }
