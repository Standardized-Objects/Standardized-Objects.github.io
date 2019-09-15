---
layout: default
title: Store Objects
parent: Object Definitions
nav_order: 1
---

# Store Object Definitions
{: .no_toc }

---

## Globaly (GIT)

Create a GIT repository to store your objects 

    git_root
    ├── obj1
    │   ├── config.yaml
    │   ├── postcreate
    │   │   ├── 000-hook.sh
    │   │   └── 000-hook2.sh
    │   └── templates
    │       └── your_templates_here.txt
    └── obj12
        ├── config.yaml
        ├── postcreate
        │   ├── 000-hook.sh
        │   └── 000-hook2.sh
        └── templates
            └── your_templates_here.txt

---

## Current path (.stdized)

Standardized searches for definitions of objects stored in a directory called .stdized in current path

    .stdized
    ├── obj1
    │   ├── config.yaml
    │   ├── postcreate
    │   │   ├── 000-hook.sh
    │   │   └── 000-hook2.sh
    │   └── templates
    │       └── your_templates_here.txt
    └── obj12
        ├── config.yaml
        ├── postcreate
        │   ├── 000-hook.sh
        │   └── 000-hook2.sh
        └── templates
            └── your_templates_here.txt

