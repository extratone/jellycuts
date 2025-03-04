# Repeat
## Notes
Repeats are pretty straight forward. They just repeat whatever code you have in them a certain amount of time.
Available Variables within repeat
1. Repeat Index.
## Syntax
```
repeat(<#Integer#>) {
	•Actions•
}
or
repeat(<#Variable#>) {
	•Actions•
}
```
## Example
```
repeat(3) {
	wait(Repeat index)
}
or
repeat(seconds) {
	wait(Repeat index)
}
```