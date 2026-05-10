# Seafloor Dark

A dark teal VSCode theme.

## Preview

![Seafloor Dark theme screenshot](images/screenshot.png)

## Installation

### From VSIX (recommended)

1. Install the packaging tool if you don't have it:
   ```
   npm install -g @vscode/vsce
   ```

2. Build the `.vsix` package from this directory:
   ```
   vsce package
   ```

3. Install it into VSCode:
   ```
   code.cmd --install-extension seafloor-dark-0.0.1.vsix
   ```

4. Restart VSCode, then select **Seafloor Dark** via `Ctrl+K Ctrl+T`.

### Updating

After making changes to the theme, repackage and reinstall:

```
vsce package
code.cmd --install-extension seafloor-dark-0.0.1.vsix
```

VSCode will replace the old version. Reload the window (`Ctrl+Shift+P` → "Reload Window") to see changes.
