# Personal Windows Configuration

My personal windows configuration using winget configure.

## How to use

### Testing configuration

> Expected output
>
> - `System is in the described configuration state.` : The program already installed on the system
> - `System is not in the described configuration state.` : The program is not installed or from a different source

```powershell
winget configure test -f winget-windows-configuration.winget
```

### Running configuration

```powershell
winget configure -f winget-windows-configuration.winget
```
