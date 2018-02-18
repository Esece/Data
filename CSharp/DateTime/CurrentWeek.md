# Current Week

``` csharp
static DateTime[] GetCurrentWeek(DateTime date)
{
    var weekStartDate = date.AddDays(-((int)date.DayOfWeek));
    return Enumerable.Range(0, 7).Select(i => weekStartDate.AddDays(i)).ToArray();
}
```

**Example**

Input: 2/17/2018

|DateTime[]|
|-----|
|2/11/2018 12:00:00 AM|
|2/12/2018 12:00:00 AM|
|2/13/2018 12:00:00 AM|
|2/14/2018 12:00:00 AM| 
|2/15/2018 12:00:00 AM| 
|2/16/2018 12:00:00 AM| 
|2/17/2018 12:00:00 AM| 
