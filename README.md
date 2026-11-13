# fcreme/scoop-terminalstyles

The Scoop bucket for [TerminalStyles](https://github.com/fcreme/TerminalStyles).

```powershell
scoop bucket add terminalstyles https://github.com/fcreme/scoop-terminalstyles
scoop install terminalstyles
```

Then, once, to load it in every new PowerShell tab:

```powershell
Import-Module TerminalStyles -DisableNameChecking; tstyles register
```

Update with `scoop update terminalstyles`, remove with `scoop uninstall terminalstyles`
(after `tstyles uninstall`, which takes out the shell loader and leaves the module to Scoop).

The manifest follows TerminalStyles' GitHub Releases: a daily workflow points it at the
latest release's `TerminalStyles-<version>.zip` and runs the install test.
