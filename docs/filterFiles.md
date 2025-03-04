# Filter File
## Notes
Filters the given files.
## Syntax
```
filterFiles(input: <#Variable#>, filterType: <#Filter Type#> , filter: <#Filter#>, sortBy: <#Sort (filterFiles)#>, order: <#Order#>, limit: <#Integer#>)
```
## Example
```
filterFiles(input: Files, filterType: All, filter: {Name: == :Meta}, sortBy: Creation Date, order: Oldest First, limit: 5)
```