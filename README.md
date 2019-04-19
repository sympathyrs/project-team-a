## Introduction
This project aims at updating the website https://csci3250-2019.github.io/project-team-a/ and promoting this repository.

Progresses
1.  Set up the file readme.md including 3 headings: Introduction, Code, and Contributors
2.  Write a short summary under Introduction
3.  Under Contributors, use include_relative to include every contributors' md file under the folder _stu
4.  At the bottom of the page, include the last updated time using site.time
5.  Create a new project board and use the Basic Kanban template, containing "To do", "In Progress", and "Done"
6.  Write a piece of C code in the file code.c and include it in readme.md 
7.  Go to the public repo of csci3250-2019.github.io in the CSCI3250 organization
8.  Edit the file to add a link of our team, and request for review from @chuckjee

## Code 
```c
{% include_relative code.c %}  
```
[![Build Status](https://travis-ci.org/csci3250-2019/project-team-a.svg?branch=master)](https://travis-ci.org/csci3250-2019/project-team-a)

## Contributors
1. {% include_relative _stu/1155110077.md %}
2. {% include_relative _stu/1155110177.md %}
3. {% include_relative _stu/1155107790.md %}
4. {% include_relative _stu/1155108254.md %}
5. {% include_relative _stu/1155109549.md %}
6. {% include_relative _stu/1155110263.md %}
7. {% include_relative _stu/1155107799.md %}

{{ site.time }}
