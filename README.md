## Best vscode-settings for Flutter and React

### Make sure you have the most current version of VSCode.

### On machine

## Clone vscode-settings
```
$ git clone https://github.com/vmontanheiro/vscode-settings.git
$ cd vscode-settings
$ code settings.json // Copy to your user settings.json
```

### Extensions install
## UNIX:

```
$ cat extensions.list | xargs -L 1 code --install-extension
```

## Windows (PowerShell, e. g. using VSCode's integrated Terminal):
```
$ code extensions.list | % { "code --install-extension $_" }
```

![Screen](https://raw.githubusercontent.com/vmontanheiro/vscode-settings/master/vscode.png)

