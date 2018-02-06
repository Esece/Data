# Day of Week

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

