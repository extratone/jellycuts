# Filter Attendees
## Notes
Filters the given Attendees. Attendees are people attending an event.
## Syntax
```
filterAttendees(input: <#Variable#>, filterType: <#Filter Type#> , filter: <#Filter#>, sortBy: <#Sort (filterAttendees)#>, order: <#Order#>, limit: <#Integer#>)
```
## Example
```
filterAttendees(input: event, filterType: Any, filter: {Is Me}, sortBy: Creation Date, order: Oldest First, limit: 5)
```