---
layout: post
title: Utility Library
subtitle: Various decorators and functions for python
gh-repo: velajua/utility_library
gh-badge: [star, fork, follow]
thumbnail-img: /assets/img/python.png
cover-img: /assets/img/python-banner_.jpg
tags: [decorators, python, selenium, redis, slack, api, ip, functions, regex]
comments: true
---

This [`repository`](https://github.com/velajua/utility_library) contains a collection of useful functions in Python, including web scraping, API integrations and day-to-day code snippets.

These functions can be easily integrated into your projects to save time and effort. The repository is organized into various sections, each containing a description of the functions included, as well as the requirements for running each of the functions.

The requirements can be installed using `pip install -r requirements.txt` 

Note that some of the functions are dependent on others, as such some *_utils.py* need to be in the same folder to properly work.

## Modules

The following modules are links to the corresponding github repositories:
*Additional information can be found in each of the links regarding their specific functions and dependencies*

- [`ip_utils`](https://github.com/velajua/utility_library/tree/main/ip_utils): A module for working with IP addresses

An IP address, or Internet Protocol address, is a unique numerical identifier assigned to every device connected to the internet. It allows devices to communicate with each other over the internet by sending and receiving data packets.

IP addresses come in two versions: IPv4 and IPv6. IPv4 addresses are 32-bit numbers expressed in decimal format, and are made up of four sets of numbers between 0 and 255, separated by periods. For example, "192.168.0.1" is a typical IPv4 address. IPv6 addresses are 128-bit numbers expressed in hexadecimal format, and are made up of eight sets of four hexadecimal digits, separated by colons. For example, "2001:0db8:85a3:0000:0000:8a2e:0370:7334" is a typical IPv6 address.

IP addresses are used by internet protocols to route data packets from one device to another over the internet. Each device connected to the internet is assigned a unique IP address, which allows it to be identified and located by other devices on the internet. IP addresses are assigned to devices by Internet Service Providers (ISPs) or other organizations that manage networks.

In addition to identifying devices on the internet, IP addresses can also be used to determine the location of a device. Geolocation services can use IP address information to determine the approximate location of a device, which can be useful for a variety of purposes, such as targeted advertising or content delivery. However, it's important to note that IP address-based geolocation is not always accurate, and can be affected by a variety of factors, such as the use of VPNs or proxies.

- [`redis_utils`](https://github.com/velajua/utility_library/tree/main/redis_utils): A module for working with the Redis database

Redis is an open-source, in-memory data structure store that can be used as a database, cache, and message broker. It supports various data structures such as strings, hashes, sets, lists, and sorted sets, and provides a rich set of commands to operate on these data structures.

Redis is often used as a fast, reliable, and scalable caching solution, due to its ability to store data entirely in memory, which makes it much faster than disk-based databases. It also provides features such as data persistence and replication for improved reliability and availability.

Some of the key features of Redis include:

High performance: Redis is designed to be extremely fast, with the ability to perform millions of operations per second.
Data structures: Redis supports a variety of data structures, including strings, hashes, sets, lists, and sorted sets, which can be used to store and manipulate data in a flexible way.
Persistence: Redis provides various mechanisms to persist data to disk, including snapshotting and append-only files.
Replication: Redis supports master-slave replication, allowing multiple Redis instances to be used for improved availability and scalability.
Lua scripting: Redis allows Lua scripts to be executed directly on the server, which can be used to implement complex data manipulations or transactions.
Redis can be accessed through a number of client libraries in various programming languages, including Python, Java, Ruby, and Node.js. The Redis commands can be sent to Redis server through the client libraries and responses can be received and parsed back.

Overall, Redis is a versatile and powerful tool for managing and storing data, and can be used in a wide range of applications, including web applications, mobile apps, and Internet of Things (IoT) devices.

- [`regex_utils`](https://github.com/velajua/utility_library/tree/main/regex_utils): A module with regex functions to validate strings, clean them and create validators.

Regular expressions (regex) are a sequence of characters that form a pattern. They are used to search, manipulate, and validate text. A regex engine takes a regex pattern and applies it to a string, looking for matches or specific patterns within the string.

Regex allows you to perform complex text searches and manipulations with just a few characters. It can match patterns such as digits, letters, specific characters, and more. You can also use special characters such as the dot (.) to match any character, or the asterisk (*) to match zero or more occurrences of the preceding character.

Regex patterns are created using a set of metacharacters, which have special meanings. For example, the caret (^) is used to match the start of a string, and the dollar sign ($) is used to match the end of a string. These metacharacters can be combined with other characters to create more complex patterns.

Regex is widely used in programming languages and text editors for tasks such as search and replace, input validation, and data parsing. It is a powerful tool for working with text and can be a valuable skill for anyone working with data or programming.

- [`selenium_utils`](https://github.com/velajua/utility_library/tree/main/selenium_utils): A module for automating web browsers with Selenium

Selenium is a popular open-source framework for automating web browsers. It provides a set of tools and APIs to automate web browsers and perform various tasks, such as testing web applications, web scraping, and web automation.

Selenium is primarily used to automate testing of web applications. It allows developers and testers to write automated test scripts in various programming languages, such as Python, Java, C#, and Ruby. These test scripts can then be executed on different web browsers, such as Chrome, Firefox, Safari, and Internet Explorer, to test the functionality of the web application under different conditions.

Selenium provides a set of APIs to interact with web elements, such as buttons, links, text fields, and dropdowns. It can simulate user actions such as clicking, typing, and scrolling. Selenium also provides the ability to capture screenshots, manage cookies and sessions, and handle pop-ups and alerts.

Selenium can be used to perform web scraping, where it can extract data from websites by navigating to web pages, extracting data from HTML elements, and saving the data in a structured format, such as CSV or JSON.

Overall, Selenium is a powerful tool for web automation and testing, and is widely used in the software development industry. It provides a flexible and reliable way to automate repetitive tasks and test the functionality of web applications.

- [`slack_utils`](https://github.com/velajua/utility_library/tree/main/slack_utils): A module for sending messages to Slack

Slack is a cloud-based team collaboration platform that is widely used in businesses and organizations of all sizes. It provides a range of features to facilitate communication and collaboration among team members, including real-time messaging, voice and video calls, file sharing, and integrations with other tools and services.

Slack allows team members to communicate and collaborate in a single platform, reducing the need for multiple tools and channels of communication. Users can create channels for specific projects or teams, and can invite other team members to join these channels. They can also send direct messages to individual team members or groups of team members.

Slack also provides a range of integrations with other tools and services, such as project management tools, customer relationship management (CRM) software, and social media platforms. These integrations allow team members to access and share information from other tools and services directly within Slack.

In addition to its core messaging and collaboration features, Slack provides a range of tools to manage teams and projects, including the ability to set reminders, create polls, and track tasks and deadlines. Slack also provides analytics and reporting tools to help teams monitor their activity and performance.

Slack can be accessed through a web interface or through its desktop and mobile apps, and is available on multiple platforms, including Windows, macOS, iOS, and Android.

Overall, Slack is a powerful tool for team collaboration and communication, and is widely used by businesses and organizations of all sizes to improve productivity, efficiency, and collaboration among team members.

- [`utils`](https://github.com/velajua/utility_library/tree/main/utils): A general-purpose module with various helper functions and decorators

In Python, a decorator is a special type of function that can modify or enhance the behavior of another function or class without changing its source code. A decorator is a higher-order function that takes another function as input and returns a new function that adds some additional behavior to the original function. Decorators are a key feature of Python and are commonly used in many frameworks and libraries.

Decorators are defined using the "@" symbol followed by the name of the decorator function. The decorator function takes a single argument, which is the function or class being decorated. The decorator function then returns a new function or class that wraps the original function or class and adds some additional behavior.

