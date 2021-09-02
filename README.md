


# python_essentials
> Basic setup required for a Python project under Visual Studio Code. To fully understand this project you want to go to the authority on how to setup a Python project under Visual Studio Code here:<br/>

- [Getting Started with Python in VS Code](https://code.visualstudio.com/docs/python/python-tutorial)<br/>
- [Python testing in Visual Studio Code](https://code.visualstudio.com/docs/python/testing)<br/>

This project is just a starting template for Python projects.

![pytest](https://github.com/perryatdmg/basic_python/blob/main/etc/img/Basic_Python.png)

## Why use an IDE?
> The following are examples of (pytest) debugging Python inside Visual Studio Code:

Here we have a typical Python methods to be unit tested:
![pytest](https://github.com/perryatdmg/basic_python/blob/main/etc/img/000.png)</br>
### Here we have at least one unit test per method:
![pytest](https://github.com/perryatdmg/basic_python/blob/main/etc/img/007.png)</br>
### In this case a unit test has indicated that either the method is not functioning as expected, (or perhaps the test case is not correct):
![pytest](https://github.com/perryatdmg/basic_python/blob/main/etc/img/001.png)</br>
### The benefits of using an IDE such as Visual Studio Code are that, (the trained eye) can quickly see which unit tests are reporting a pass, (in green) and unit tests are indicating an issue, (in red):
![pytest](https://github.com/perryatdmg/basic_python/blob/main/etc/img/002.png)</br>
Additionally, the editor portion shows the unit test case, (that requires attention) with an additional "red line":
![pytest](https://github.com/perryatdmg/basic_python/blob/main/etc/img/003.png)</br>
In the console/terminal portion of the screen, the actual report from the pytest framework is supplied to the software developer, (in blue):
![pytest](https://github.com/perryatdmg/basic_python/blob/main/etc/img/004.png)</br>
In this case the unit test was incorrect, but as soon as the test was corrected, the "red line" is removed, (by the Pytest extension for Visual Studio Code):
![pytest](https://github.com/perryatdmg/basic_python/blob/main/etc/img/007.png)</br>
Further, the console report is not reporting no errors:
![pytest](https://github.com/perryatdmg/basic_python/blob/main/etc/img/008.png)</br>
![pytest](https://github.com/perryatdmg/basic_python/blob/main/etc/img/009.png)</br>
With the IDE we can set breakpoints and catch the code at the precise line of source requiring our attention:
![pytest](https://github.com/perryatdmg/basic_python/blob/main/etc/img/010.png)</br>
Resulting in a fully operational test case suite, (or all green):
![pytest](https://github.com/perryatdmg/basic_python/blob/main/etc/img/012.png)</br>

