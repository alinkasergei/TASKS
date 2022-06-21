int n1, n2, n3; 

Console.Write("input first number: ");
n1 = Convert.ToInt32(Console.ReadLine());

Console.Write("input second number: ");
n2 = Convert.ToInt32(Console.ReadLine());

Console.Write("input third number: ");
n3 = Convert.ToInt32(Console.ReadLine());

if (n1 == n2)
    if (n2 == n3)
        Console.WriteLine("три числа равны");
    else 
    {
        if (n1 > n3)
            Console.Write("n1, n2 max numbers: ");
    
        else 
        {
            Console.Write("n3 max number: ");
        }
    }       
else
{
    if (n1 == n3)
        if (n1 > n2)
           Console.Write("n1, n3 max numbers: "); 
        else 
        {
            Console.Write("n2 max number: ");
        } 
    else 
    {
        if (n2 == n3)
            if (n2 > n1)
                Console.Write("n2, n3 max numbers: "); 
            else
            {
                Console.Write("n1 max number: ");    
            }
        else
        {
            if (n1 > n2)
                if (n1 > n3)
                    Console.Write("n1 max number: ");   
                else
                {
                    Console.Write("n3 max number: ");   
                } 
            else
                {
                    if (n2 > n3)
                        Console.Write("n2 max number: ");   
                    else 
                    {
                       Console.Write("n3 max number: ");    
                    }
                }         
        }    
    }

}
