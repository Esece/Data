# Fibonacci Numbers

Example
``` csharp
FibonacciNumbers.Enumerate().Take(46);  [ 1, 1, 2, 3, 5, 8,... 1836311903 ]
```

Source
``` csharp
class FibonacciNumbers
{
    public static IEnumerable<long> Enumerate()
    {
        long first = 1;
        long second = 1;

        yield return first;
        yield return second;

        while (true)
        {
            long current = first + second;

            if (current > 0)
            {
                yield return current;

                first = second;
                second = current;
            }
            else
            {
                break;
            }
        }
    }
}
```
