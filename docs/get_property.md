# Get Property
## Notes
When using a variable you can add this onto the end of it to get any property about that variable.
## Syntax
```
<#Variable#>.get(<#Property#>)
```
## Example
```
dictionary(meta) >> META
var meta = META.get(keys)
or
text("${Shortcut Input.as(Dictionary).get(keys)"}
```