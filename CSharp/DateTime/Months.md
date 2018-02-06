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


``` csharp
Enum.GetValues(typeof(DayOfWeek)).Cast<DayOfWeek>().ToDictionary(d => (int)d, d => DateTimeFormatInfo.CurrentInfo.GetDayName(d))
```
|Key|Value|
|-----|-----|
|1|Sunday|
|2|Monday|
| : | : |
|5|Friday|
|6|Saturday|

