# Windows Bash Explorer Context Menu
The registry keys necessary to add the shift+right-click context menu to the Windows 10 Explorer context menu similar to the Command Prompt shift+right-click context menu option.

!["Open Bash window here" in the Explorer shift+right-click context menu](screenshot.png?raw=true)

## Usage
Simply open the `add_bash.reg` file to add the Bash context menu option. To remove this menu option in the future, open the `remove_bash.reg` file.

## Modification
To make the context menu option available on right-click only, simply change the lines with the "Extended" keys to the following:

```
"Extended"=-
```