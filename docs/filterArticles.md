# Filter Articles
## Notes
Filters the given articles.
## Syntax
```
filterArticles(input: <#Variable#>, filterType: <#Filter Type#> , filter: <#Filter#>, sortBy: <#Sort (filterArticles)#>, order: <#Order#>, limit: <#Integer#>)
```
## Example
```
filterArticles(input: Articles, filterType: All, filter: {Name: .contains : NPR}, sortBy: Creation Date, order: Oldest First, limit: 5)
```