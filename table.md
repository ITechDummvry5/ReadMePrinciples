Got it — since this is **`table.md`**, not a README, it should be focused purely on the **naming and structure reference tables**, without README-style explanations.

The main thing I would fix is the **Reference Learning section**: it should use `[technology]`, not `[name]`, because `ref-lrn-` is specifically for technologies like Git, Linux, Docker, SQL, and Bash.

# Repository Structure

Format: `[number]-[prefix]-[name]`, using lowercase kebab-case.

| Category    | Root Folder       | Prefix  | Pattern                     | Description                        |
| ----------- | ----------------- | ------- | --------------------------- | ---------------------------------- |
| Projects    | `project-proj/`   | `proj-` | `[number]-proj-[name]`      | Main development projects          |
| Clones      | `clone-cln/`      | `cln-`  | `[number]-cln-[name]`       | Recreation of existing projects    |
| Learning    | `learning-lrn/`   | `lrn-`  | `[number]-lrn-[technology]` | Learning and practicing technology |
| Experiments | `experiment-exp/` | `exp-`  | `[number]-exp-[name]`       | Testing ideas and concepts         |
| Tools       | `tools-tool/`     | `tool-` | `[number]-tool-[name]`      | Useful tools and scripts           |
| Templates   | `template-tpl/`   | `tpl-`  | `[number]-tpl-[name]`       | Reusable starter projects          |

## Learning Types

| Learning Type      | Root Folder     | Prefix     | Pattern                         | Brief Description                     |
| ------------------ | --------------- | ---------- | ------------------------------- | ------------------------------------- |
| Standard Learning  | `learning-lrn/` | `lrn-`     | `[number]-lrn-[technology]`     | Structured technology learning        |
| Reference Learning | `learning-lrn/` | `ref-lrn-` | `[number]-ref-lrn-[technology]` | Commands, syntax, and quick reference |

---

## Projects

### Root

```text
project-proj/
│
├── README.md
│
├── 01-proj-ecommerce/
├── 02-proj-banadero-management/
├── 03-proj-scholarship-finder/
└── ...
```

### Each Project

```text
[number]-proj-[name]/
│
├── README.md
├── LICENSE
├── .gitignore
│
├── docs/
│   ├── overview.md
│   ├── setup.md
│   ├── features.md
│   └── screenshots/
│
├── src/
│   ├── index.html
│   │
│   ├── assets/
│   │   ├── images/
│   │   ├── icons/
│   │   ├── fonts/
│   │   └── videos/
│   │
│   ├── css/
│   │   ├── style.css
│   │   └── responsive.css
│   │
│   └── js/
│       ├── script.js
│       └── modules/
│
└── ...
```

---

## Clones

### Root

```text
clone-cln/
│
├── README.md
│
├── 01-cln-apple-store/
├── 02-cln-netflix/
├── 03-cln-spotify/
└── ...
```

### Each Clone

```text
[number]-cln-[name]/
│
├── README.md
├── LICENSE
├── .gitignore
│
└── src/
    ├── index.html
    │
    ├── assets/
    │   ├── images/
    │   ├── icons/
    │   ├── fonts/
    │   └── videos/
    │
    ├── css/
    │   ├── style.css
    │   └── responsive.css
    │
    └── js/
        ├── script.js
        └── modules/
```

---

## Learning

### Root

```text
learning-lrn/
│
├── README.md
│
├── 01-lrn-javascript/
├── 02-lrn-css/
├── 03-lrn-html/
│
├── 01-ref-lrn-git/
├── 02-ref-lrn-linux/
├── 03-ref-lrn-github-cli/
├── 04-ref-lrn-docker/
└── ...
```

### Each Learning Project

```text
[number]-lrn-[technology]/
│
├── README.md
│
├── docs/
│   ├── 01-[technology]-[concept].md
│   ├── 02-[technology]-[concept].md
│   ├── 03-[technology]-[concept].md
│   └── ...
│
├── src/
│   ├── css/
│   │   └── style.css
│   │
│   └── js/
│       └── script.js
│
├── 01-[technology]-[concept]/
├── 02-[technology]-[concept]/
├── 03-[technology]-[concept]/
│
└── ...
```

### Each Reference Learning Project

```text
[number]-ref-lrn-[technology]/
│
├── README.md
├── commands.md
└── notes.md
```

---

## Experiments

### Root

```text
experiment-exp/
│
├── README.md
│
├── 01-exp-api-testing/
├── 02-exp-ui-animation/
├── 03-exp-database/
└── ...
```

### Each Experiment

```text
[number]-exp-[name]/
│
├── README.md
├── LICENSE
├── .gitignore
│
├── docs/
│   ├── overview.md
│   ├── notes.md
│   └── results.md
│
├── src/
│   ├── index.html
│   ├── css/
│   │   └── style.css
│   │
│   └── js/
│       └── script.js
│
└── ...
```

---

## Tools

### Root

```text
tools-tool/
│
├── README.md
│
├── 01-tool-image-converter/
├── 02-tool-file-renamer/
├── 03-tool-json-formatter/
└── ...
```

### Each Tool

```text
[number]-tool-[name]/
│
├── README.md
├── LICENSE
├── .gitignore
│
├── docs/
│   ├── overview.md
│   ├── setup.md
│   └── usage.md
│
├── src/
│   ├── index.html
│   ├── css/
│   │   └── style.css
│   │
│   └── js/
│       └── script.js
│
└── ...
```

---

## Templates

### Root

```text
template-tpl/
│
├── README.md
│
├── 01-tpl-portfolio-website/
├── 02-tpl-landing-page/
├── 03-tpl-orbit-slider/
└── ...
```

### Each Template

```text
[number]-tpl-[name]/
│
├── index.html
├── css/
│   └── style.css
├── js/
│   └── script.js
└── img/
```

---
