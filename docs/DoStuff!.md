# Functions
## Notes
Functions can be used with or without parameter names. When you are calling a function with parameter names you can re-arrange the parameters in any order you want. If you are running without parameter names then you must leave the parameters in the order shown in the documentation. A function's output can be sent to a variable by adding >> ID to the end of function call.
## Syntax
```
//Used with named parameters
alert(alert: <#String (Allows Variables)#>, title: <#String (Allows Variables)#>, cancel: <#Boolean#>)
//Used without named parameters
alert(<#String (Allows Variables)#>, <#String (Allows Variables)#>, <#Boolean#>)
```
## Example
```
//Used with named parameters
alert(alert: "Hello World!", title: "Jellycuts", cancel: true)
//Used without named parameters
alert("Hello World!", "Jellycuts", true)
```