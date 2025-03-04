# Append File
## Notes
Appends contents to the end of a file.
## Syntax
```
appendFile(input: <#String (Allows Variables)#>, path: <#String (Allows Variables)#>, newLine: <#Boolean#>)
```
## Example
```
appendFile(input: "This is a new line ${Clipboard}", path: "JellycutsHelper/Text.txt", newLine: true)
```