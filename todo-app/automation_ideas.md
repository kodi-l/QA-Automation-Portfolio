# Automation Strategy – To-Do App

## What I Would Automate First:

| Feature         | Priority | Automation Type        | Notes                             |
|----------------|----------|------------------------|-----------------------------------|
| Add Task       | High     | Smoke / Regression     | Core functionality                |
| Delete Task    | High     | Regression             | Ensure task list updates properly |
| Toggle Complete| High     | Functional / UI        | Checkbox functionality            |

---

## Leave Manual (For Now):

| Feature         | Reason                          |
|----------------|----------------------------------|
| Editing Tasks  | Buggy – best for exploratory     |
| Edge cases     | Rare input combos                |
| UI validation  | Needs visual regression tools    |

---

## Tools I Would Use:
- **Selenium + Python** (for UI automation)
- **Postman** (if API exists for task CRUD)
- **Jest/Cypress** (if app is React-based)

---

## Bonus Ideas:
- Add test for **localStorage persistence**
- Add **cross-browser compatibility** tests
- Eventually implement **data-driven testing**
