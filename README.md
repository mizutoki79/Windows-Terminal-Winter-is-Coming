# Winter is Coming for [Window Terminal](https://github.com/microsoft/terminal)

This color schema is inspired by [Winter is Coming Theme for VSCode](https://github.com/johnpapa/vscode-winteriscoming)

## Installation

1. Open your `profiles.json` settings for Windows Terminal. You can use shortcut `Ctrl + ,` to open it with default editor.

2. Find `schemes` section in that settings file.

3. Add a schema to the list.
For example.

```
{
    ...
    "schemes" :
    [
        {
            "background" : "#011627",
            "black" : "#011627",
            "blue" : "#2472c8",
            "brightBlack" : "#666666",
            "brightBlue" : "#3b8eea",
            "brightCyan" : "#29b8db",
            "brightGreen" : "#23d18b",
            "brightPurple" : "#d670d6",
            "brightRed" : "#f14c4c",
            "brightWhite" : "#e5e5e5",
            "brightYellow" : "#f5f543",
            "cyan" : "#11a8cd",
            "foreground" : "#cccccc",
            "green" : "#0dbc79",
            "name" : "Winter is Coming (Dark Blue)",
            "purple" : "#bc3fbc",
            "red" : "#cd3131",
            "white" : "#e5e5e5",
            "yellow" : "#e5e510"
        },
        {
            "background" : "#0C0C0C",
            "black" : "#0C0C0C",
            "blue" : "#0037DA",
            "brightBlack" : "#767676",
            "brightBlue" : "#3B78FF",
            "brightCyan" : "#61D6D6",
            "brightGreen" : "#16C60C",
            "brightPurple" : "#B4009E",
            "brightRed" : "#E74856",
            "brightWhite" : "#F2F2F2",
            "brightYellow" : "#F9F1A5",
            "cyan" : "#3A96DD",
            "foreground" : "#CCCCCC",
            "green" : "#13A10E",
            "name" : "Campbell",
            "purple" : "#881798",
            "red" : "#C50F1F",
            "white" : "#CCCCCC",
            "yellow" : "#C19C00"
        }
        ...
    ]
}
```

4. Replace `"colorScheme" : "Winter is Coming (Dark Blue)",` for your profile.

For example:

```
{
    ...4
    "profiles" :
    [
        {
            "acrylicOpacity" : 0.5,
            "closeOnExit" : true,
            "colorScheme" : "Winter is Coming (Dark Blue)",
            "commandline" : "C:\\Program Files\\PowerShell\\6\\pwsh.exe",
            "cursorColor" : "#FFFFFF",
            "cursorShape" : "bar",
            "fontFace" : "Cascadia Code PL",
            "fontSize" : 10,
            "guid" : "{574e775e-4f2a-5b96-ac1e-a2962a402336}",
            "historySize" : 9001,
            "icon" : "ms-appx:///ProfileIcons/{574e775e-4f2a-5b96-ac1e-a2962a402336}.png",
            "name" : "PowerShell Core",
            "padding" : "0, 0, 0, 0",
            "snapOnInput" : true,
            "startingDirectory" : "%USERPROFILE%",
            "useAcrylic" : false
        },
        ...
    ]
    ...
}
```
