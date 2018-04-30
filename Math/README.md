# Math

### Fibonacci Numbers

Example
``` csharp
FibonacciNumbers.Enumerate().Take(46);  [ 1, 1, 2, 3, 5, 8,... 1836311903 ]
```

-----

### PI
Get up to 15 or more characters long
``` csharp
var pi = PI.GetString(30);
Console.WriteLine(pi);  // "3.141592653589793238462643383279"
```

Also available in the standard library
``` csharp
Math.PI.ToString();  // "3.14159265358979"
```
