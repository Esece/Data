# Months

``` csharp
Enumerable.Range(1, 12).ToDictionary(i => i, i => String.Format("({0:D2}) {1}", i, DateTimeFormatInfo.CurrentInfo.GetMonthName(i)))
```
|Key|Value|
|-----|-----|
|1|(01) January|
|2|(02) February|
| : | : |
|11|(11) November|
|12|(12) December|


