# moodleToMD

---

## About
Scrap any moodle and turn moodle classes into MD files

---
## Web-Scrapping
### TOC struct
Tags from page navigation to get wanted date

#### UFPR VIRTUAL
````html
https://ufprvirtual.ufpr.br/
````
##### Login
````html
https://ufprvirtual.ufpr.br/login/index.php
<form id="login">
    <input id="username">
    <input id="password">
````
##### My Courses
````html
https://ufprvirtual.ufpr.br/my/
<div class="course_title">
<div id="nav-drawer">
    <li data-key="mycourses">
        <ul class="collapse">
            <li class="list-group-item"> 
                -> course_id
````
##### Course page
```html
https://ufprvirtual.ufpr.br/course/view.php?id={course_id}
<div id='page'>
    <div class='page-header-headings'>
    <div id='page-content'>
        <ul class='timelines'>
            <li class='timeline-clickable'>
            <li class='moveablesection'>
                <ul class='subtimelines'>
                    <li class='subtimeline'>
```
## More info
Package structured based on:
- [Dead Simple Python: Project Structure and Imports](https://dev.to/codemouse92/dead-simple-python-project-structure-and-imports-38c6)
- [Structuring Your Project](https://docs.python-guide.org/writing/structure/)
