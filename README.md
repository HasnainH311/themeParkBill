 internal class Program
    {
        static void Main(string[] args)
        {
            int costPerPerson = 15;
            Console.WriteLine("How many people in the group");
            int numOfPeople = Convert.ToInt32(Console.ReadLine());
            int totalCost = (costPerPerson * numOfPeople);
            if (numOfPeople > 6)
            {
                totalCost = totalCost - 5;
            }
            else
            {
                totalCost = totalCost;
            }
            Console.WriteLine("Total cost is " + totalCost);
            Console.ReadLine();
        }
    }
