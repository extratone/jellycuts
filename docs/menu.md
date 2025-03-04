# Menu
## Notes
Menus allow you to give the user a bunch of options to work with. All options in the upper list must have a case associated with it.
## Syntax
```
menu(<#String (Allows Variables)#>, <#Array#>) {
	case(<#String (No Variables)#>):
		•Actions•
	
	case(<#String (No Variables)#>):
		•Actions•
	
}
```
## Example
```
menu("Choose an action", ["Log Water", "Workout"]) {
	case("Log Water"):
		runShortcut(Log Water)
	case("Workout"):
		runShortcut(Workout)
}
```