## Naming convention

Format: `[number]-category-what-it-is`, all lowercase kebab-case.

| Category    | Root Folder       | Prefix  | Pattern                     | Description                     |
| ----------- | ----------------- | ------- | --------------------------- | ------------------------------- |
| Projects    | `project-proj/`   | `proj-` | `[number]-proj-[name]`      | Main development projects       |
| Clones      | `clone-cln/`      | `cln-`  | `[number]-cln-[name]`       | Recreation of existing projects |
| Learning    | `learning-lrn/`   | `lrn-`  | `[number]-lrn-[technology]` | Learning and practice projects  |
| Experiments | `experiment-exp/` | `exp-`  | `[number]-exp-[name]`       | Testing ideas and concepts      |
| Tools       | `tools-tool/`     | `tool-` | `[number]-tool-[name]`      | Useful utilities and scripts    |
| Templates   | `template-tpl/`   | `tpl-`  | `[number]-tpl-[name]`       | Reusable starter projects       |







* **Projects** — Complete or ongoing applications and larger development projects.

  Example: `01-proj-ecommerce` 

### Root

project-proj/
│
├── README.md
│
├── 01-proj-ecommerce/
├── 02-proj-banadero-management/
├── 03-proj-scholarship-finder/
└── ...

### Each Projects

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



* **Clone** — Projects that recreate or imitate the design, features, or functionality of an existing website, application, or system.

    Example: `01-clone-apple-store`

### Root

clone-cln/
│
├── README.md
│
├── 01-apple-store/
├── 02-netflix/
├── 03-spotify/
└── ...

### Each Clones

[number]-cln-[name]/
│
├── README.md
├── LICENSE
├── .gitignore
│
├── docs/
│   ├── overview.md
│   ├── setup.md
│   ├── features.md
│   ├── reference.md
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
└──  ...



* **Learning** — Projects created while learning or practicing a technology or concept.

  Example: `01-lrn-javascript`

### Root

learn-lrn/
│
├── README.md
├── terminologies-[technology].md
├── design-pattern-[technology].md
│
├── 01-lrn-javascript/
├── 02-lrn-css/
├── 03-lrn-html/
└── ...

### Each Learning Project

[number]-lrn-[technology]/
│
├── README.md
│
├── docs/
│   ├── 01-[topic].md
│   ├── 02-[topic].md
│   ├── 03-[topic].md
│   └── ...
│
├── src/                    # Optional
│   ├── css/
│   │   └── style.css
│   │
│   └── js/
│       └── script.js
│
├── 01-[topic]/
├── 02-[topic]/
├── 03-[topic]/
│
└── ...



* **Experiments** — Small tests, prototypes, and ideas used to explore a concept or technology.

  Example: `01-exp-api-testing`

### Root

experiment-exp/
│
├── README.md
│
├── 01-exp-api-testing/
├── 02-exp-ui-animation/
├── 03-exp-database/
└── ...

### Each Experiment

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
│   └── js/
│       └── script.js
│
└── ...



* **Tools** — Useful utilities, scripts, or developer tools.

  Example: `01-tool-image-converter`

### Root

tools-tool/
│
├── README.md
│
├── 01-tool-image-converter/
├── 02-tool-file-renamer/
├── 03-tool-json-formatter/
└── ...

### Each Tool

01-tool-[name]/
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
│   └── js/
│       └── script.js
│
└── ...


* **Templates** — Reusable starter projects, layouts, components, or boilerplates.

  Example: `01-tpl-portfolio-website`

### Root

template-tpl/
│
├── README.md
│
├── 01-tpl-portfolio-website/
├── 02-tpl-landing-page/
├── 03-tpl-orbit-slider/
└── ...

### Each Template

[number]-tpl-[name]/
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
│   ├── assets/
│   │   ├── images/
│   │   ├── icons/
│   │   └── fonts/
│   │
│   ├── css/
│   │   └── style.css
│   │
│   └── js/
│       └── script.js
│
└── ...

