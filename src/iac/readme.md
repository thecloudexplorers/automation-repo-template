# Purpose

All bicep should be placed in this folder.

- Bicep files declaring individual reusable resources should be placed in az-resources
- Bicep modules should be placed in the az-module

Example structure:

```html
+-- iac
    |
    +-- az-modules
    |   |
    |   +-- resource-group-a-module.bicep
    |   |
    |   +-- resource-group-a-module.bicep
    |
    +-- az-resources
    |   |
    |   +-- aks.bicep
    |   |
    |   +-- key-vault.bicep
    |   |
    |   +-- app-insights.bicep
    |   |
    |   +-- law.bicep
    |
```
