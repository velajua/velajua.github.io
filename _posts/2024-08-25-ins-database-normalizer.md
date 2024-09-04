---
layout: post
title: INS Database Normalizer
subtitle: A series of executables which allow for proper consolidation and normalization of Excel databases.
gh-repo: velajua/INS_database_normalizer
gh-badge: [star, fork, follow]
thumbnail-img: /assets/img/ins-thumb.png
cover-img: /assets/img/python-banner_.jpg
tags: [Python, Excel, TKinter, Executable, Application]
comments: true
---

This [`repository`](https://github.com/velajua/INS_database_normalizer) contains a suite of executables which allow for proper consolidation and normalization of Excel databases, through a series of commands, which allow to concatenate, fix values and map values to fix the disease databases used by the INS (Instituto Nacional de la Salud), in Colombia.

## Requirements

The repository, contains executables as well as the source code.

Python 3.x

tkinter (for GUI)

The requirements for the different executables' source code can be installed by using `pip install -r <path_to_desired_executable>/_codigo_fuente/requirements.txt`

## Usage
- Each executable contains its own readme (LEEME.pdf).

## Notes
- INS does not use Cloud Services, as such all is handled through Excel files.
- Not all databases are loaded, as some are bigger than 50MB, they can be found in the `bases_finales` folder.
- All PII has been deleted.
