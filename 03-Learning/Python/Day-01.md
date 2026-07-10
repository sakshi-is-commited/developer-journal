## Modules
A module is simply a single Python file ending in .py. It is the smallest unit of code organisation.
- Purpose: group related functions, classes, and variables together to avoid monolithic files.

## Packages
A package is a directory that holds multiple modules or even sub-packages.
- Purpose: Provide a hierarchical, nested structure to organise large codebases by domain logic

## Imports
An import is the mechanism to link your modules and packages together so they can share code namespaces. In project architecture, there are two standard ways to structure imports: Absolute imports and Relative imports.

## Project Architecture
In python project architecture, modules are individual files, packages are directories containing modules, imports link them together, __init__.py initialises those packages. Together they for the structural blueprint that makes python code scalable, maintainable and reusable.

## Separation of Concerns
Separation of Concerns (SoC) is a core software design principle that breaks a complex system into distinct, manageable modules, where each module addresses a specific responsibility or feature.

## Single Responsibility Principle
The Single Responsibility Principle (SRP) states that a class or module should have one, and only one, reason to change. This means each class should focus on doing exactly one job, making the code far easier to read, test, and maintain as your application scales.