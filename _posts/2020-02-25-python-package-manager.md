---
layout: post
title: Package Manager
permalink: "/python-package-manager"
type: documentation
---

# Python | Package Manager

---

-   A package manager is used to install, upgrade, remove and manager python packages and libraries. There are multiple packager managers available for the python, but `pip` is the most common python package manager which comes built-in to python these days. You can use `pip --version` in your command prompt to see the installed version of `pip`. 

``` 
C:\Users\t6chopra>pip --version
pip 19.3.1 from c:\users\t6chopra\appdata\local\programs\python\python37\lib\site-packages\pip (python 3.7)
```
-  Almost any common library or package in python can be installed using `pip` in command prompt.

## PIP
-   To install a library. `pip install <library_name>`

``` 
C:\Users\t6chopra>pip install numpy
Requirement already satisfied: numpy in c:\users\t6chopra\appdata\local\programs\python\python37\lib\site-packages (1.18.1)
``` 

-   To install a library. `pip install <library_name> --upgrade`
-   To uninstall/remove a library. `pip uninstall <library_name>`
-   To install all the libraries of the project from requirements.txt. `pip install -r requirements.txt`