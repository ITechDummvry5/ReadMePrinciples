
````md
# Charles Codebase

A structured collection of development projects, clones, learning exercises, experiments, tools, and reusable templates.

The repository uses a consistent naming convention and category-based organization to keep development work easy to find and maintain.

---

## Categories

| Category    | Root Folder       | Prefix  | Purpose                            |
| ----------- | ----------------- | ------- | ---------------------------------- |
| Projects    | `project-proj/`   | `proj-` | Main development projects          |
| Clones      | `clone-cln/`      | `cln-`  | Recreations of existing projects   |
| Learning    | `learn-lrn/`      | `lrn-`  | Learning and practice projects     |
| Experiments | `experiment-exp/` | `exp-`  | Tests, prototypes, and ideas       |
| Tools       | `tools-tool/`     | `tool-` | Utilities and developer tools      |
| Templates   | `template-tpl/`   | `tpl-`  | Reusable starters and boilerplates |

---

## Naming Convention

All folders follow:

```text
[number]-category-[name]
[number]-[topic]
````

Example:

```text
01-proj-ecommerce
01-cln-apple-store
01-lrn-javascript
01-exp-api-testing
01-tool-image-converter
01-tpl-portfolio-website
```

Names use:

* lowercase
* kebab-case
* sequential numbering
* category prefixes

---

## Documentation

Detailed organization and folder structures:

**[`table.md`](table.md)**

Deployment information for projects hosted through Vercel:

**[`vercel.md`](vercel-deploy.md)**

---

## Purpose

This repository serves as a personal development codebase for organizing projects, learning materials, experiments, tools, clones, and reusable templates in one consistent structure.

````

This way:

```text
README.md   → What this repository is
table.md    → Full naming + folder structure
vercel.md   → Vercel deployment information open for the public
````

Much cleaner than putting all the detailed folder structures inside the main README.
