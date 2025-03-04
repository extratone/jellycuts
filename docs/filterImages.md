# Filter Images
## Notes
Filters the given images.
## Syntax
```
filterImages(input: <#Variable#>, filterType: <#Filter Type#> , filter: <#Filter#>, sortBy: <#Sort (filterImages)#>, order: <#Order#>, limit: <#Integer#>)
```
## Example
```
filterImages(input: Images, filterType: All, filter: {Width: == : 1024, Height: == 1024}, sortBy: Creation Date, order: Oldest First, limit: 5)
```