## SOQL Notes


### Date Functions

Allow to **group** or **filter** data by date-periods  (like day, calendar month, fiscal year)

```sql
SELECT CALENDAR_YEAR(CreatedDate), SUM(Amount)
		FROM Opportunity
			GROUP BY CALENDAR_YEAR(CreatedDate)

```

![](./img/cal-year-sum-1.png)



### Questions

1. 