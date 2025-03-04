# Filter Contacts
## Notes
Filters the given contacts. Placing All Contacts in the input will allow you to filter all of your contacts.
## Syntax
```
filterContacts(input: <#Variable#>, filterType: <#Filter Type#> , filter: <#Filter#>, sortBy: <#Sort (filterContacts)#>, order: <#Order#>, limit: <#Integer#>)
```
## Example
```
filterContacts(input All Contacts, filterType: All, filter: {Name: == : Zach}, sortBy: Creation Date, order: Oldest First, limit: 5)
```