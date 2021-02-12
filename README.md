# HTML-CSS-Cheatsheet
> This is a quick reference guide for commonly used HTML and CSS tags, attributes, styling, and more. An exercise in creating a static web page, simply building the page of tables and content helped solidify my knowledge of the concepts.

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Setup](#setup)
* [Features](#features)
* [Status](#status)
* [Inspiration](#inspiration)
* [Contact](#contact)

## General info
This project uses HTML and CSS to create a static webpage containing a working table of contents comprised of hyperlinks, and tables of commonly used HTML and CSS language. I will be continually adding to this page as my knowledge on the subjects expands, as this page can be a reference point written in language I know how to understand.

## Technologies
* Coded in Visual Studio Code
* HTML5
* CSS

## Setup
Installation instructions coming soon.

## Code Examples
An Example of a section including a table, that uses an id attribute for Table of Contents purposes. The ID attribute within the heading is a selector when styling.
Using the `span` tag, I was able to properly style code snippets to appear differently when displayed.
```html
<section id="tables">     
    <h2 id="HTML Tables">HTML Tables</h2>
    <table>
        <thead>
            <tr>
                <th>Tag</th>
                <th>Name</th>
                <th>Definition</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><span class="code">&lt;table&gt;</span></td>
                <td>Table</td>
                <td>Creates a blank table (No rows or columns)</td>
            </tr>
            <tr>
                <td><span class="code">&lt;tr&gt;</span></td>
                <td>Table Row</td>
                <td>Creates a blank row</td> 
            </tr>
            <tr>
                <td><span class="code">&lt;td&gt;</span></td>
                <td>Table Data</td>
                <td>This is where you write the content of a cell</td> 
            </tr>
            <tr>
                <td><span class="code">&lt;thead&gt;</span></td>
                <td>Table Head</td>
                <td>Used to separate the head of the table from the rest</td> 
            </tr>
            <tr>
                <td><span class="code">&lt;th&gt;</span></td>
                <td>Table Head</td>
                <td>Used within the <span class="code">&lt;thead&gt;</span> as column headers</td> 
            </tr>
            <tr>
                <td><span class="code">&lt;tbody&gt;</span></td>
                <td>Table Body</td>
                <td>Used to separate the body of the table from the head</td> 
            </tr>
            <tr>
                <td><span class="code">&lt;tfoot&gt;</span></td>
                <td>Table Footer</td>
                <td>Used to separate the footer of the table from the rest</td> 
            </tr>
        </tbody>
    </table>
```
## Features
List of features ready and TODOs for future development
* Contains information regarding basic HTML Tags, Semantic HTML, commonly used CSS elements, etc.
* Styled to be visually appealing, making code snippits stand out
* Uses Semantic HTML for accessibility purposes

To-do list:
* Continually add additional HTML and CSS concepts
* Add examples of code usage to further term definitions

## Status
Project is: _in progress_

## Inspiration
This project was inspired by the studyguides I used to scrawl out in my notebook at Syracuse University. A much more organized, searchable document, will provide me even better support in my learning journey. Part of the Full-Stack Developer course at Codecademy. 

## Contact
Created by [Jesse Scheinbart](https://www.linkedin.com/in/jesse-scheinbart/) - feel free to contact me!
