# Purpose

This folder contains IaC files that are used as controllers or orchestrators.
Meaning scripts which are intended to utilize one or more modules to deploy
resources.

Example structure:

```html
📦az-controllers
 ┣ 📂defenderplans
 ┃ ┣ 📂samples
 ┃ ┃ ┗ localDeploy.ps1
 ┃ ┣ 📂test
 ┃ ┃ ┣ happy-flow.params.json
 ┃ ┃ ┣ invalid-setting.params.json
 ┃ ┃ ┗ unhappy-flow.params.json
 ┃ ┣ 📜defenderplans.bicep
 ┃ ┗ 📜readme.md
 ┣ 📂subscriptionvending
 ┃ ┣ 📂samples
 ┃ ┃ ┗ localDeploy.ps1
 ┃ ┣ 📂test
 ┃ ┃ ┣ happy-flow.params.json
 ┃ ┃ ┣ invalid-setting.params.json
 ┃ ┃ ┗ unhappy-flow.params.json
 ┃ ┣ 📜subscriptionvending.bicep
 ┃ ┗ 📜readme.md
 ┗ 📜readme.md
```
