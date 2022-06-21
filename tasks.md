int n;
int count;
Console.WriteLine("input a number ");
n = Convert.ToInt32(Console.ReadLine());
count = 1;
if (n > 0)
{
    while (count < n)
    {
        if ( count % 2 == 0)
          Console.WriteLine(count);
        
        count++;
    }
}
else
{
    while (n < 0)
    {
        if ( n % 2 == 0)
          Console.WriteLine(n);
        
        n++;

    }
}
   Console.WriteLine("number is odd");
}

