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

    standardized repo add example https://github.com/example/example.git

### GitHub repository

    standardized repo add example https://github.com/example/example.git -t <PERSONAL ACCESS TOKEN>

### SSH repository

    standardized repo add example https://github.com/example/example.git --ssh

---

## Update repositories

    standardized repo update
