# Purpose

The pipeline gallery is a repository for storing pipeline definitions, jobs, and
steps that can be used in Azure DevOps Pipelines. It is intended to be used as a
place to store reusable pipeline components.

Jobs and steps are defined in YAML files. These files can be used directly in
your pipelines, or they can be used as templates for creating new jobs and
steps. For consistency the jobs and steps should be stored separate folders.
In addition it is recommended to use the `.yml` file extension for
these files.

Example structure:

```html
📦pipline-gallery
 ┣ 📂jobs
 ┃ ┗ 📜palceholder.md
 ┣ 📂steps
 ┃ ┗ 📜palceholder.md
 ┗ 📜palceholder.md
```
