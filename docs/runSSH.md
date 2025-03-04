# Run Script Over SSH
## Notes
Runs the given script over an SSH connection.
## Syntax
```
runSSH(host: <#String (Allows Variables)#>, port: <#String (Allows Variables)#>, user: <#String (Allows Variables)#>, auth: <#Type (WFSSHAuthenticationType)#>, password: <#String (Allows Variables)#>, script: <#Variable#>)
```
## Example
```
runSSH(host: "pi_address", port: "22", user: "raspberry", auth: password, password: "••••••••", script: Shortcut Input)
```