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

Create a GIT repository to store your objects.

    git_root
    ├── obj01
    │   ├── config.yaml
    │   ├── postcreate
    │   │   ├── 000-hook.sh
    │   │   └── 001-hook.sh
    │   └── templates
    │       └── your_templates_here.txt
    └── obj02
        ├── config.yaml
        ├── postcreate
        │   ├── 000-hook.sh
        │   └── 001-hook.sh
        └── templates
            └── your_templates_here.txt

---

## Current path (.stdized)

Standardized searches for definitions of objects stored in a directory called .stdized in current path.

    .stdized
    ├── obj01
    │   ├── config.yaml
    │   ├── postcreate
    │   │   ├── 000-hook.sh
    │   │   └── 001-hook.sh
    │   └── templates
    │       └── your_templates_here.txt
    └── obj02
        ├── config.yaml
        ├── postcreate
        │   ├── 000-hook.sh
        │   └── 001-hook.sh
        └── templates
            └── your_templates_here.txt
