---
name: Bug
about: השתמשי בתבנית זו לפתיחת באג.
labels: bug
body:
- type: markdown
  attributes:
    value: "## ברוכה הבאה!"
- type: markdown
  attributes:
    value: "מוזמנת להעלות את הבעיה בה נתקלת, השתדלי לספק את מירב המידע והפרטים על המקרה כדי לאפשר עזרה מהירה וממוקדת."
- type: dropdown
  id: version
  attributes:
    label: גירסת דוטנט
    options:
      - .NET 8
      - .NET 7
      - .NET 6
  validations:
    required: true
- type: input
  id: github-link
  attributes:
    label: קישור לריפו בגיטהאב (חובה Public)
  validations:
    required: true
---
