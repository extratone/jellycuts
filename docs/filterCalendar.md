# Filter Calendar Events
## Notes
Filters the given events. Placing All Events in the input will allow you to filter all of your calendar events.
## Syntax
```
filterCalendar(input: <#Variable#>, filterType: <#Filter Type#> , filter: <#Filter#>, sortBy: <#Sort (filterCalendar)#>, order: <#Order#>, limit: <#Integer#>)
```
## Example
```
filterCalendar(input: All Events, filterType: All, filter: {Name: == : Test}, sortBy: Creation Date, order: Oldest First, limit: 20)
```