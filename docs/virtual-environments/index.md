---
title: Virtual Environments
has_children: true
nav_order: 3
---

Virtual environments allow you to create isolated project environments with their own dependencies and Python versions.  This prevents conflicts between projects and ensures that each application uses the packages and versions it was developed and tested witih.

Without a virtual environment packages are installed globally to your host machine.  This can lead to version conflicts between projects.

This section covers several common tools used to manage virtual environments and dependencies in Python. Typically you need only choose and use one of these tools to manage your virtual environment and packages.

* UV - A fast modern Python package and environments manager
* Poetry - A popular tool that manages dependencies and virtual environments
* Pip + venv - The most basic virtual environment and package set up using Python's built-in `venv` module and pip directly.
