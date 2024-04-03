---
name: Bug
about: "השתמשי בתבנית זו לפתיחת באג."
labels: bug
body:
  - type: markdown
    attributes:
      value: "## Wellcome!"
  - type: markdown
    attributes:
      value: "come on."
  - type: dropdown
    id: version
    attributes:
      label: ".NET Version"
      options:
        - .NET 8
        - .NET 7
        - .NET 6
    validations:
      required: true
  - type: input
    id: github-link
    attributes:
      label: "link to GitHub"
    validations:
      required: true
---
