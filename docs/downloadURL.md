# Get Contents of URL
## Notes
Downloads the contents at the given URL.
## Syntax
```
downloadURL(url: <#String (Allows Variables)#>, method: <#Type (WFHTTPMethod)#>, headers: <#Dictionary#>, requestType: <#Type (WFHTTPBodyType)#>, request: <#Dictionary#>)
```
## Example
```
downloadURL(url: "https://jellycuts.com", method: POST, headers: {}, requestType: Json, request: {"name": "Zach"})
```