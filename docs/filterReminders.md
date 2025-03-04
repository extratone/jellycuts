# Filter Reminders
## Notes
Filters the given reminders. Placing All Reminders in the input will allow you to filter all of your reminders.
## Syntax
```
filterReminders(input: <#Variable#>, filterType: <#Filter Type#> , filter: <#Filter#>, sortBy: <#Sort (filterReminders)#>, order: <#Order#>, limit: <#Integer#>)
```
## Example
```
filterReminders(input: All Reminders, filterType: All, filter: {Name: == : Test}, sortBy: Creation Date, order: Oldest First, limit: 20)
```