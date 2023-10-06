# Purpose

All **generic** scripts should be placed here. If multiple script languages are used a subfolder per language should be created
All specific scripts should be placed in the [pipelines](../../pipelines/readme.md) folder as explained in hte link.


https://poshcode.gitbook.io/powershell-practice-and-style/best-practices/building-reusable-tools

Example structure:

```html
+-- scripts
    |
    +-- PowerShell
    |   |
    |   +-- functions
    |   |   |
    |   |   +-- New-DemoFunction.ps1
    |   |   |
    |   |   +-- Set-DemoSetting.ps1
    |   |
    |   +-- fullDemoScript.ps1
    |
    +-- CLI
    |   |
    |   +-- exampleScript.sh
    |   |
    |   +-- demoScript.sh
    |
```
