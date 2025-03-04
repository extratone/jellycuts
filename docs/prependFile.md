# Prepend File
## Notes
Prepends contents to the file.
## Syntax
```
prependFile(input: <#String (Allows Variables)#>, path: <#String (Allows Variables)#>, newLine: <#Boolean#>)
```
## Example
```
prependFile(input: "This is a new line ${Clipboard}", path: "JellycutsHelper/Text.txt", newLine: true)
```