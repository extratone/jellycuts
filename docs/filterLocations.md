# Filter Locations
## Notes
Filters the given locations.
## Syntax
```
filterLocations(input: <#Variable#>, filterType: <#Filter Type#> , filter: <#Filter#>, sortBy: <#Sort (filterLocations)#>, order: <#Order#>, limit: <#Integer#>)
```
## Example
```
filterLocations(input: locationArray, filterType: Any, filter: {City: == : Philadelphia}, sortBy: Title, order: A to Z, limit: 20)
```