---
layout: post
title: Utility Library
subtitle: Various decorators and functions for python
gh-repo: velajua/utility_library
gh-badge: [star, fork, follow]
tags: [decorators, python, selenium, redis, slack, api, ip, functions]
comments: true
---

This repository contains a collection of useful functions in Python, including web scraping, API integrations and day-to-day code snippets.

These functions can be easily integrated into your projects to save time and effort. The repository is organized into various sections, each containing a description of the functions included, as well as the requirements for running each of the functions.

The requirements can be installed using `pip install -r requirements.txt` 

Note that some of the functions are dependent on others, as such some *_utils.py* need to be in the same folder to properly work.

## Modules

The following modules are included in this repository:

- [`ip_utils`](https://github.com/velajua/utility_library/ip_utils): A module for working with IP addresses
- [`redis_utils`](redis_utils/README.md): A module for working with the Redis database
- [`selenium_utils`](selenium_utils/README.md): A module for automating web browsers with Selenium
- [`slack_utils`](slack_utils/README.md): A module for sending messages to Slack
- [`utils`](utils/README.md): A general-purpose module with various helper functions and decorators
