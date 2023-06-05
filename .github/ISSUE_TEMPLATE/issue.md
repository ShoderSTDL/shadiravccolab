---
name: Issue
about: Please provide as much detail as possible to convey the history of your problem.
---

body:

- type: dropdown
  id: issue-type
  attributes:
  label: Issue Type
  description: What type of issue would you like to report?
  multiple: true
  options: - Feature Request - Documentation Feature Request - Others
  validations:
  required: true