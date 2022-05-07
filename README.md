# moodleToMD
Scrap any moodle and turn moodle classes into MD files

## Web-Scrapping
### TOC struct

#### UFPR VIRTUAL
##### Login
````angular2html
root = https://ufprvirtual.ufpr.br/
login = https://ufprvirtual.ufpr.br/login/index.php

<form id="login">
    <input id="username">
    <input id="password">
````
##### My Courses
````angular2html
my = https://ufprvirtual.ufpr.br/my/

<div class="course_title">
<div id="nav-drawer">
    <li data-key="mycourses">
        <ul class="collapse">
            <li class="list-group-item">
````
##### Course page
```html
<div id='page'>
    <div class='page-header-headings'>
    <div id='page-content'>
        <ul class='timelines'>
            <li class='timeline-clickable'>
            <li class='moveablesection'>
                <ul class='subtimelines'>
                    <li class='subtimeline'>
```
