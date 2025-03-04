# Get File
## Notes
Retrieves the file at a given path. It can also open a document picker if there is no path provided and the picker parameter is set to true.
## Syntax
```
getFile(picker: <#Boolean#>, path: <#String (Allows Variables)#>, error: <#Boolean#>, multiple: <#Boolean#>)
```
## Example
```
getFile(picker: false, path: "JellycutsHelper/meta.json", error: false, multiple: false)
```