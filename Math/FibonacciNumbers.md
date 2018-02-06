# Fibonacci Numbers

``` csharp
public class FibonacciNumbers
{
    public static IEnumerable<int> Enumerate()
    {
        int first = 1;
        int second = 1;

        yield return first;
        yield return second;

        while (true)
        {
            int current = first + second;

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
