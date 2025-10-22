# nvm

Install [NVM](https://github.com/coreybutler/nvm-windows)

to enable npm;

```bash
# This allows scripts to run only for the current PowerShell session, so it's safer.
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process

# Change policy for user
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser

# Change policy for the whole system (requires admin privileges)
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope LocalMachine
```
