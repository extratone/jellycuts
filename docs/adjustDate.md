# Adjust Date
## Notes
Adjusts the given date by adding or subtracting the given duration. If you use any get operation you do not need a duration.
## Syntax
```
adjustDate(operation: <#Type (WFAdjustOperation)#>, duration: <#Time#>, date: <#String (Allows Variables)#>)
```
## Example
```
adjustDate(operation: Add, duration: 10 min, date: "10:30 pm")
```