---
layout: default
title: Repositories
parent: CLI
nav_order: 2
---

# Manage repositories
{: .no_toc }

---

## Add repositories

### Public repository

    standardized repo add example https://github.com/example/objects.git

### Private GitHub repository

    standardized repo add example https://github.com/example/objects.git -t <PERSONAL ACCESS TOKEN>

### Private SSH repository

    standardized repo add example git@github.com:example/objects.git --ssh

---

## Update repositories

    standardized repo update
