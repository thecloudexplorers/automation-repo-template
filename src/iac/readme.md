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
    |   +-- resource-group-a-module
    |   |   |
    |   |   +-- module
    |   |   |   |
    |   |   |   +-- resource-group-a-module.bicep
    |   |   |
    |   |   +-- examples
    |   |   |   |
    |   |   |   +-- resource-group-a-module-example.ps1
    |   |   |
    |   |   +-- tests
    |   |       |
    |   |       +-- resource-group-a-module.tests.ps1
    |   |
    |   |
    |   +-- resource-group-b-module
    |       |
    |       +-- module
    |       |   |
    |       |   +-- resource-group-b-module.bicep
    |       |
    |       +-- examples
    |       |   |
    |       |   +-- resource-group-b-module-example.ps1
    |       |
    |       +-- tests
    |           |
    |           +-- resource-group-b-module.tests.ps1
    |
    +-- az-resources
    |   |
    |   +-- aks
    |   |   |
    |   |   +-- aks.bicep
    |   |   |
    |   |   +-- aks-example.bicep
    |   |   |
    |   |   +-- aks-example.ps1
    |   |   |
    |   |   +-- aks.tests.ps1    
    |   |
    |   +-- key-vault
    |   |   |
    |   |   +-- key-vault.bicep
    |   |   |
    |   |   +-- key-vault-example.bicep
    |   |   |
    |   |   +-- key-vault-example.ps1
    |   |   |
    |   |   +-- key-vault.tests.ps1        
    |   |   
    |   +-- app-insights
    |   |   |
    |   |   +-- app-insights.bicep
    |   |   |
    |   |   +-- app-insights-example.bicep
    |   |   |
    |   |   +-- app-insights-example.ps1
    |   |   |
    |   |   +-- app-insights.tests.ps1        
    |   |
    |   +-- law
    |   |   |
    |   |   +-- law.bicep
    |   |   |
    |   |   +-- law-example.bicep
    |   |   |
    |   |   +-- law-example.ps1
    |   |   |
    |   |   +-- law.tests.ps1            
    |
```
