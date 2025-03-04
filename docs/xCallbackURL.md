# Open X-Callback URL
## Notes
Run an x-callback URL.
## Syntax
```
xCallbackURL(url: <#String (Allows Variables)#>, custom: <#Boolean#>, success: <#String (Allows Variables)#>, cancel: <#String (Allows Variables)#>, error: <#String (Allows Variables)#>, customXSuccess: <#Boolean#>, xSuccess: <#String (Allows Variables)#>)
```
## Example
```
xCallbackURL(url: "shortcuts://x-callback-url/run-shortcut?name=Calculate%20Tip&input=text&text=24.99.", custom: true, success: "x-success", cancel: "x-cancel", error: "x-error", customXSuccess: false, xSuccess: "shortcuts://callback")
```