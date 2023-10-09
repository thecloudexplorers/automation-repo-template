# Purpose

This folder contains IaC files that are used as a unit of code reuse. A module
can contain a single resource or set of resources, and can be called
from controllers. This allows deployments to be small, manageable components,
and reuse common pieces.

Example structure:

```html
📦az-modules
 ┣ 📂Microsoft.Authorization
 ┃ ┗ 📂policyassignments
 ┃   ┣ 📂samples
 ┃   ┃ ┗ localDeploypolicies.ps1
 ┃   ┣ 📂test
 ┃   ┃ ┣ happy-flow.params.json
 ┃   ┃ ┣ invalid-setting.params.json
 ┃   ┃ ┗ unhappy-flow.params.json
 ┃   ┣ deploy.bicep
 ┃   ┗ 📜readme.md
 ┣ 📂Microsoft.KeyVault
 ┃ ┗ 📂vaults
 ┃   ┣ 📂samples
 ┃   ┃ ┗ localDeploypolicies.ps1
 ┃   ┣ 📂test
 ┃   ┃ ┣ happy-flow.params.json
 ┃   ┃ ┣ invalid-setting.params.json
 ┃   ┃ ┗ unhappy-flow.params.json
 ┃   ┣ deploy.bicep
 ┃   ┗ 📜readme.md
 ┣ 📂Microsoft.Network
 ┃ ┣ 📂dnszones
 ┃ ┃ ┣ 📂samples
 ┃ ┃ ┃ ┗ localDeploypolicies.ps1
 ┃ ┃ ┣ 📂test
 ┃ ┃ ┃ ┣ happy-flow.params.json
 ┃ ┃ ┃ ┣ invalid-setting.params.json
 ┃ ┃ ┃ ┗ unhappy-flow.params.json
 ┃ ┃ ┣ deploy.bicep
 ┃ ┃ ┗ 📜readme.md
 ┃ ┗ 📂virtualnetworks
 ┃   ┣ 📂samples
 ┃   ┃ ┗ localDeploypolicies.ps1
 ┃   ┣ 📂test
 ┃   ┃ ┣ happy-flow.params.json
 ┃   ┃ ┣ invalid-setting.params.json
 ┃   ┃ ┗ unhappy-flow.params.json
 ┃   ┣ deploy.bicep
 ┃   ┗ 📜readme.md
 ┣ 📂Microsoft.Storage
 ┃ ┗ 📂storageaccounts
 ┃   ┣ 📂samples
 ┃   ┃ ┗ localDeploypolicies.ps1
 ┃   ┣ 📂test
 ┃   ┃ ┣ happy-flow.params.json
 ┃   ┃ ┣ invalid-setting.params.json
 ┃   ┃ ┗ unhappy-flow.params.json
 ┃   ┣ deploy.bicep
 ┃   ┗ 📜readme.md
 ┗ 📜readme.md
```
