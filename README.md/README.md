@@ -1,76 +1,281 @@
# 0x01. AirBnB clone - Web static
# 0x00. AirBnB clone - The console

## Learning Objectives:bulb:
What you should learn from this project:
## 0x00.Table of contents

* What is HTML
* How to create an HTML page
* What is a markup language
* What is the DOM
* What is an element / tag
* What is an attribute
* How does the browser load a webpage
* What is CSS
* How to add style to an element
* What is a class
* What is a selector
* How to compute CSS Specificity Value
* What are Box properties in CSS
* [0x01 Introduction]
* [0x02 Environment]
* [0x03 Installation]
* [0x04 Testing]
* [0x05 Usage]
* [0x06 Authors]

---
## 0x01 Introduction

### [0. Inline styling]
* Write an HTML page that displays a header and a footer.
Team project to build a clone of [AirBnB](https://www.airbnb.com/).

The console is a command interpreter to manage objects abstraction between objects and how they are stored.

### [1. Head styling]
* Write an HTML page that displays a header and a footer by using the style tag in the head tag (same as 0-index.html)

The console will perform the following tasks:

### [2. CSS files]
* Write an HTML page that displays a header and a footer by using CSS files (same as 1-index.html)
* create a new object
* retrive an object from a file
* do operations on objects
* destroy an object

### Storage

### [3. Zoning done!]
* Write an HTML page that displays a header and footer by using CSS files (same as 2-index.html)
All the classes are handled by the `Storage` engine in the `FileStorage` Class.

## 0x02 Environment

### [4. Search!]
* Write an HTML page that displays a header, footer and a filters box with a search button.
<!-- ubuntu -->
<a href="https://ubuntu.com/" target="_blank"> <img height="" src="https://img.shields.io/static/v1?label=&message=Ubuntu&color=E95420&logo=Ubuntu&logoColor=E95420&labelColor=2F333A" alt="Suite CRM"></a> <!-- bash --> <a href="https://www.gnu.org/software/bash/" target="_blank"> <img height="" src="https://img.shields.io/static/v1?label=&message=GNU%20Bash&color=4EAA25&logo=GNU%20Bash&logoColor=4EAA25&labelColor=2F333A" alt="terminal"></a> <!-- python--> <a href="https://www.python.org" target="_blank"> <img height="" src="https://img.shields.io/static/v1?label=&message=Python&color=FFD43B&logo=python&logoColor=3776AB&labelColor=2F333A" alt="python"></a> </a> <!-- vim --> <a href="https://www.vim.org/" target="_blank"> <img height="" src="https://img.shields.io/static/v1?label=&message=Vim&color=019733&logo=Vim&logoColor=019733&labelColor=2F333A" alt="Suite CRM"></a> <!-- vs code --> <a href="https://code.visualstudio.com/" target="_blank"> <img height="" src="https://img.shields.io/static/v1?label=&message=Visual%20Studio%20Code&color=5C2D91&logo=Visual%20Studio%20Code&logoColor=5C2D91&labelColor=2F333A" alt="Suite CRM"></a> </a><!-- git --> <a href="https://git-scm.com/" target="_blank"> <img height="" src="https://img.shields.io/static/v1?label=&message=Git&color=F05032&logo=Git&logoColor=F05032&labelColor=2F333A" alt="git distributed version control system"></a> <!-- github --> <a href="https://github.com" target="_blank"> <img height="" src="https://img.shields.io/static/v1?label=&message=GitHub&color=181717&logo=GitHub&logoColor=f2f2f2&labelColor=2F333A" alt="Github"></a>
 <!-- Style guidelines -->
* Style guidelines:
  * [pycodestyle (version 2.7.*)](https://pypi.org/project/pycodestyle/)
  * [PEP8](https://pep8.org/)

All the development and testing was runned over an operating system Ubuntu 20.04 LTS using programming language Python 3.8.3. The editors used were VIM 8.1.2269, VSCode 1.6.1 and Atom 1.58.0 . Control version using Git 2.25.1.

### [5. More filters]
* Write an HTML page that displays a header, footer and a filters box.
## 0x03 Installation

```bash
git clone https://github.com/Huckiel7/AirBnB_clone.git
```

### [6. It's (h)over]
* Write an HTML page that displays a header, footer and a filters box with dropdown.
change to the `AirBnb` directory and run the command:

```bash
 ./console.py
```

### [7. Display results]
* Write an HTML page that displays a header, footer, a filters box with dropdown and results.
### Execution

In interactive mode

### [8. More details]
* Write an HTML page that displays a header, a footer, a filter box (dropdown list) and the result of the search.
```bash
$ ./console.py
(hbnb) help
Documented commands (type help <topic>):
========================================
EOF  help  quit
### [9. Full details](./100-index.html)
* Write an HTML page that displays a header, footer, a filters box with dropdown and results.
(hbnb)
(hbnb)
(hbnb) quit
$
```

in Non-interactive mode

### [10. Flex]
* Improve the Places section by using Flexible boxes for all Place articles
```bash
$ echo "help" | ./console.py
(hbnb)
Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)
### [11. Responsive design](./102-index.html)
* Improve the page by adding responsive design to display correctly in mobile or small screens.
Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb)
$
```

## 0x04 Testing

### [12. Accessibility]
* Improve the page by adding Accessibility support
All the test are defined in the `tests` folder.

---
### Documentation

* Modules:

```python
python3 -c 'print(__import__("my_module").__doc__)'
```

* Classes:

```python
python3 -c 'print(__import__("my_module").MyClass.__doc__)'
```

* Functions (inside and outside a class):

```python
python3 -c 'print(__import__("my_module").my_function.__doc__)'
```

and

```python
python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'
```

### Python Unit Tests

* unittest module
* File extension ``` .py ```
* Files and folders star with ```test_```
* Organization:for ```models/base.py```, unit tests in: ```tests/test_models/test_base.py```
* Execution command: ```python3 -m unittest discover tests```
* or: ```python3 -m unittest tests/test_models/test_base.py```

### run test in interactive mode

```bash
echo "python3 -m unittest discover tests" | bash
```

### run test in non-interactive mode

To run the tests in non-interactive mode, and discover all the test, you can use the command:

```bash
python3 -m unittest discover tests
```


## 0x05 Usage

* Start the console in interactive mode:

```bash
$ ./console.py
(hbnb)
```

* Use help to see the available commands:

```bash
(hbnb) help
Documented commands (type help <topic>):
========================================
EOF  all  count  create  destroy  help  quit  show  update
(hbnb)
```

* Quit the console:

```bash
(hbnb) quit
$
```

### Commands

> The commands are displayed in the following format *Command / usage / example with output*
* Create

> *Creates a new instance of a given class. The class' ID is printed and the instance is saved to the file file.json.*
```bash
create <class>
```

```bash
(hbnb) create BaseModel
'Number given'
(hbnb)
```

* Show

```bash
show <class> <id>
```

```bash
(hbnb) show BaseModel 'Number shown'
[BaseModel] (a) [BaseModel] ('Number shown') {'id': ''Number shown' ', 'created_at': datetime.datetimeme}
(hbnb)
```

* Destroy

> *Deletes an instance of a given class with a given ID.*
> *Update the file.json*
```bash
(hbnb) create User
'Number shown'
(hbnb) destroy User x
(hbnb) show User x
** no instance found **
(hbnb)
```

* all

> *Prints all string representation of all instances of a given class.*
> *If no class is passed, all classes are printed.*
```bash
(hbnb) create BaseModel
'Number shown'
(hbnb) all BaseModel
["[BaseModel] ('Number shown') [BaseModel] ('Number shown') {'id': ''Number shown'', 'created_at': datetime.datetimetetime, 'name': 'My First Model', 'my_number': 89}"]
["[BaseMode
```
* count
> *Prints the number of instances of a given class.*
```bash
(hbnb) create City
'Number shown'
(hbnb) create City
'Number shown'
(hbnb) count City
2
(hbnb)
```
* update
> *Updates an instance based on the class name, id, and kwargs passed.*
> *Update the file.json*
```bash
(hbnb) create User
'Number shown'
(hbnb) update User 'Number shown' email "Huckielsukai7@gmail.com"
(hbnb) show User 'Number shown'
[User] (s) 
```
## Authors
Huckiel Sukai < Huckielsukai7@gmail.com >
Trevoland Nagoor < Trevolandn26@gmail.com >

