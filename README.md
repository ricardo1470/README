> # How to create your README
---
![Readme](https://img.shields.io/badge/readme-OK-green.svg?colorB=00C106) ![commits](https://img.shields.io/badge/commits-53-blue.svg)

---
![README](https://bulldogjob.com/system/readables/covers/000/001/455/max_res/8-10-2018.png)
---
> ## Table of Contents

* [What is Markdown](#What-is-Markdown)
* [What is it for](#What-is-it-for)
* [Structure of a readme](#Structure-of-a-readme)
  * [Introduction](#Introduction)
  * [Project information](#Project-information)
  * [Documentation](#Documentation)
  * [Extra information](#Extra-information)
* [Basic writing and formatting syntax](#Basic-writing-and-formatting-syntax)
  * [Headings](#Headings)
  * [Styling text](#Styling-text)
  * [Quoting text](#Quoting-text)
  * [Quoting code](#Quoting-code)
  * [Links](#Links) 
  * [tables](#tables)
  * [Lists](#Lists)
  * [Nested Lists](#Nested-Lists)
  * [Images](#Images)
    * [Local](Local)
    * [Outside](#Outside)
  * [Format](#Format)

---

A readme is much more than plain text, a readme is what visitors first observe in a repository, so we must have a little attention when creating it so we can capture the attention of visitors, in addition to being colorful it will cause a good impression, and will give confidence.
Which suggests that the code is more likely to have attention to detail and maintenance.

Now let's start by knowing a little about what **md** is. `md` or **marckdown**, what it is and what it is for.
 
### What is Markdown

Markdown is an easy way to add formatting to web texts. With format we refer to italics, bold, lists, and more, in plain text - for example, the text that we find in the HTML viewer of blog editors, or in Windows Notepad, to make the concept more affordable-. Markdown was originally created by **John Gruber**, with the help of **Aaron Swartz**, with the purpose of creating a plain text that is easy to write and easy to read, and that could be easily and validly converted to XHTML.

### What is it for
Now that we've talked about what Markdown is, we have to see what it's for. The emphasis we will put is clearly web, but there are other things that can be done with Markdown. For example, to-do lists.

> ## Structure of a readme

### Introduction
In this section we must offer a summary of what the project consists of, that is, we must give a summary, clear and concise idea of what the project consists of.
 
### Project information
Here we must offer the technical status information of the project. The version it is in, the bugs, the latest build, the technologies used, etc.

### Documentation
This is the most important part. This is where we must specify everything we must do to launch the project. What files to download, how to build the database if needed, configuration of startup paths, etc.

### Extra information
In this section we must add additional information that users can use to clarify details that they have not understood in the rest of the readme or contact information such as social networks, email, etc.

> ## Basic writing and formatting syntax

### Headings
To create a heading, add one to six **#** symbols before your heading text. The number of **#** you use will determine the size of the heading.

```
# The largest heading
## The second largest heading
###### The smallest heading

```
# The largest heading
## The second largest heading
###### The smallest heading

### Styling text
You can indicate emphasis with bold, italic, or strikethrough text.

| style                | sintax          | keyboard            | example                   | output             |
| ---------------------|-----------------|---------------------|---------------------------|--------------------|
| bold                 | ** ** or __ __  | command/control + b |  ```**This is bold text**```| **bold**               |
| italic               | * * or _ _      | command/control + i |  ```* italicized *```     | *italicized*         |
|Strikethrough         |  ~~ ~~          |                     |   ```~~mistaken~~ ```      | ~~mistaken~~           |
|Bold and nested italic| ** ** and _ _   |                     | ```**_extremely_ important**``` | **_extremely important_**|
|All bold and italic   | *** ***         |                     |  ```***text is important*** ```| ***text is important***  |

### Quoting text
You can quote text with a >.
```
In the words of Abraham Lincoln:

> Pardon my French
```
In the words of Abraham Lincoln:

> Pardon my Frenc

### Quoting code
You can call out code or a command within a sentence with single backticks. The text within the backticks will not be formatted.
```
Use `git status` to list all new or modified files that haven't yet been committed.
```
Use `git status` to list all new or modified files that haven't yet been committed.

### Links
You can create an inline link by wrapping link text in brackets [ ], and then wrapping the URL in parentheses ( ). You can also use the keyboard shortcut command + k to create a link.
```
This site was built using [GitHub Pages](https://pages.github.com/).
```
This site was built using [GitHub Pages](https://pages.github.com/)

* You can also create links to the files in your folder

```
[file](./file)
```
[file](./file)

* You can also create links to other places in your readme
```
[tables](#tables)
```
[tables](#tables)

### tables

`you can create tables:`
```
|col1|col2|col3|
|----|----|----|
|row |    |    |
|row2|    |    |
|row3|    |    |
```
|col1|col2|col3|
|----|----|----|
|row |    |    |
|row2|    |    |
|row3|    |    |

### Lists
You can make an unordered list by preceding one or more lines of text with `-` or `*`.
```
- George Washington
- John Adams
- Thomas Jefferson
```
- George Washington
- John Adams
- Thomas Jefferson

To order your list, precede each line with a number.
```
1. James Madison
2. James Monroe
3. John Quincy Adams
```
1. James Madison
2. James Monroe
3. John Quincy Adams
### Nested Lists
You can create a nested list by indenting one or more list items below another item.

```
1. First list item
   - second nested list item
     - third nested list item
```

1. First list item
   - second nested list item
     - third nested list item

### Images
you can add locally and externally hosted images
 * Local
 In order to link an image from our repository, you must upload the image to the repository where you want to host the image and copy the url assigned to it.

 `HTML` tags can be used to manipulate the image, thus adjusting the `width` and `height`.

 `alternative text` + `url`
 ```html
 <a href="alternative text"><img src="url" align="middle" width="desired width" height="desired heigh"></a>
 ```
 ```html
 <a href="logo github"><img src="https://github.com/ricardo1470/README/blob/master/img/logo_github.png" align="middle" width="100" height="50"></a>
 ```
 <a href="logo github"><img src="https://github.com/ricardo1470/README/blob/master/img/logo_github.png" align="middle" width="100" height="50"></a>

 * Outside
 in the same way that images are added locally, it can be done with images that are hosted on external servers to `github`.
 ```html
 <a href="alternative text"><img src="url" align="middle" width="desired width" height="desired heigh"></a>
 ```
 ```html
 <a href="logo github"><img src="https://e7.pngegg.com/pngimages/93/461/png-clipart-github-computer-icons-logo-readme-github-logo-monochrome.png" align="middle" width="100" height="50"></a>
 ```
 <a href="logo github"><img src="https://e7.pngegg.com/pngimages/93/461/png-clipart-github-computer-icons-logo-readme-github-logo-monochrome.png" align="middle" width="100" height="50"></a>


### Format

 you can format code snippets, according to the language in which you are working or to which you want to refer

 To add format to the code we must add the name of the language after creating the code block with \```(referenced language)```, in this way the code will be formatted with that language.

 \```referenced language

code

\```

\```python

code

\```

\```ruby

code

\```

 for example:

 > code in language `Python`:

 raw code:
 ```
#!/usr/bin/python3
def fizzbuzz():
    for i in range(1, 101):
        if (i % 3 == 0 and i % 5 == 0):
            print("FizzBuzz", end=" ")
        elif (i % 3 == 0):
            print("Fizz", end=" ")
        elif (i % 5 == 0):
            print("Buzz", end=" ")
        else:
            print("{:d}".format(i), end=" ")

 ```
 formatted code:
 \```python
 ```python
#!/usr/bin/python3
def fizzbuzz():
    for i in range(1, 101):
        if (i % 3 == 0 and i % 5 == 0):
            print("FizzBuzz", end=" ")
        elif (i % 3 == 0):
            print("Fizz", end=" ")
        elif (i % 5 == 0):
            print("Buzz", end=" ")
        else:
            print("{:d}".format(i), end=" ")
 ```

 > code in `ruby`:

 raw code:
 ```
#!/usr/bin/env ruby
puts ARGV[0].scan(/^\d{10}$/)
```
formatted code:
\```ruby
 ```ruby
#!/usr/bin/env ruby
puts ARGV[0].scan(/^\d{10}$/)
```
> code in `bash`:

raw code:
 ```
#!/bin/bash
rm *[~]
```
formatted code:
\```bash
 ```bash
#!/bin/bash
rm *[~]
```
> code in `c`:

raw code:
 ```
int main(void)
{
	puts("\"Programming is like building a multilingual puzzle");
	return (0);
}

```
formatted code:
\```c
 ```c
int main(void)
{
	puts("\"Programming is like building a multilingual puzzle");
	return (0);
}
```
---
> ## Built with
this project was built in: `html`, `marckdown`

---
> ## Expressions of Gratitude
---
* `Tell others about this project`
* `invite you for a beer` 🍺 `or a coffee` ☕ [<img src="https://github.com/ricardo1470/MEVN/blob/main/src/public/images/paypal.png" alt="Github logo" width="34">](https://paypal.me/ricardo1470?locale.x=es_XC)
---

> ## contact 💬

<div align="center">

<h2>
    Contact with me<img src="https://github.com/ricardo1470/ricardo1470/blob/master/img/Handshake.gif" height="32px">
</h2>

| [<img src="https://github.com/ricardo1470/ricardo1470/blob/master/img/GitHub.png" alt="Github logo" width="34">](https://github.com/ricardo1470/README/blob/master/README.md) | [<img src="https://github.com/ricardo1470/ricardo1470/blob/master/img/email.png" alt="email logo" height="32">](mailto:ricardo.alfonso.camayo@gmail.com) | [<img src="https://github.com/ricardo1470/ricardo1470/blob/master/img/linkedin-icon.png" alt="Linkedin Logo" width="32">](https://www.linkedin.com/in/ricardo-alfonso-camayo/) | [<img src="https://github.com/ricardo1470/ricardo1470/blob/master/img/twitter.png" alt="Twitter Logo" width="30">](https://twitter.com/RICARDO1470) |
|:---:|:---:|:---:|:---:|

---

## License
*`How to create your README` is open source and therefore free to download and use without permission.*

<a href="url"><img src="https://www.holbertonschool.com/holberton-logo.png" align="middle" width="100" height="30"></a>

---
