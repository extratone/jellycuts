# Get Key
## Notes
When using a variable you can add this onto the end of it to get any key from it.
## Syntax
```
<#Variable#>.key(<#Key#>)
```
## Example
```
dictionary(meta) >> META
var meta = META.key(names)
or
text("${Shortcut Input.as(Dictionary).key(names)"}
```