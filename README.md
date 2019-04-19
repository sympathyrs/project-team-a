## Introduction
This project aims at updating the website [https://csci3250-2019.github.io/project-team-a/](https://csci3250-2019.github.io/project-team-a/ 'Team-A') and promoting this repository.

**Progresses**
1. Set up the file readme.md including 3 headings: Introduction, Code, and Contributors.
2. Write a short summary under Introduction.
3. Under Contributors, use include_relative to include every contributors' md file under the folder _stu.
4. At the bottom of the page, include the last updated time using site.time.
5. Create a new project board and use the Basic Kanban template, containing "To do", "In Progress", and "Done".
6. Write a piece of C code in the file code.c and include it in readme.md.
7. Go to the public repo of csci3250-2019.github.io in the CSCI3250 organization.
8. Edit the file to add a link of our team, and request for review from @chuckjee.

## Code 
```c
{% include_relative code.c %}  
```
[![Build Status](https://travis-ci.org/csci3250-2019/project-team-a.svg?branch=master)](https://travis-ci.org/csci3250-2019/project-team-a)

## Contributors
* {% include_relative _stu/1155110077.md %}
* {% include_relative _stu/1155110177.md %}
* {% include_relative _stu/1155107790.md %}
* {% include_relative _stu/1155108254.md %}
* {% include_relative _stu/1155109549.md %}
* {% include_relative _stu/1155110263.md %}
* {% include_relative _stu/1155107799.md %}
* {% include_relative _stu/1155108603.md %}
* {% include_relative _stu/1155108766.md %}

Last updated: {{ site.time }}
