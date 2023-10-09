# Purpose

This folder contains IaC files that are used as a unit of code reuse. A module
can contain a single resource or set of resources, and can be called
from controllers. This allows deployments to be small, manageable components,
and reuse common pieces.

you to break down deployments into smaller, more
manageable components, and reuse common pieces.

Example structure:

```html
📦az-modules
 ┣ 📂Microsoft.Authorization
 ┃ ┗ 📂policyassignments
 ┃   ┣ 📂samples
 ┃   ┣ 📂test
 ┃   ┣ 📜readme.md
 ┣ 📂Microsoft.KeyVault
 ┃ ┣ 📂Microsoft.Authorization
 ┃ ┣ 📂Microsoft.KeyVault
 ┃ ┣ 📂Microsoft.Network
 ┃ ┗ 📂Microsoft.Storage
 ┣ 📂Microsoft.Network
 ┃ ┣ 📂Microsoft.Authorization
 ┃ ┣ 📂Microsoft.KeyVault
 ┃ ┣ 📂Microsoft.Network
 ┃ ┗ 📂Microsoft.Storage
 ┣ 📂Microsoft.Storage
 ┃ ┣ 📂Microsoft.Authorization
 ┃ ┣ 📂Microsoft.KeyVault
 ┃ ┣ 📂Microsoft.Network
 ┃ ┗ 📂Microsoft.Storage
 ┗ 📜readme.md
```
