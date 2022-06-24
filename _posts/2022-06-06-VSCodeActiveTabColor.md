---
title: VSCode Active Tab Background Color
date: 2022-06-06 12:00:00 -500
categories: [vscode]
tags: [vscode]
---

# Change the color of the active tab in VSCode

Open settings.json and add the following to the workbench.colorTheme section.
```json
    "workbench.colorCustomizations": {
        "tab.activeBackground": "#8d8888"
        "tab.inactiveBackground": "#ff0000"
    }
```

**Alternative:**

File --> Preferences --> Settings and search for workbench.colorTheme and select edit in settings.json
Add the snippet above to the file and save.
Change the color to suit you.