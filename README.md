# Code Refactoring

It is important for a programmer to write code that is readable and accessible to anyone that might interact with it.

It is good practice to write code with a logical structure containing semantic elelments. Code needs to have accessible attributes that clarify the message for end users and a title that is descriptive and concise at the same time. 

<br>

# Original code files

I started off with the following **HTML** and **CSS** files for a one-page website:

- [HTML](https://github.com/MoeCancode/Code-Refactoring/blob/main/Original_code/index.html)
- [CSS](https://github.com/MoeCancode/Code-Refactoring/blob/main/Original_code/style.css)

The goal was to refactor the code to make it more accessible and easy-to-read without changing the look of the webpage we have.

<br>

### **Several changes were made to the code files and I will explain what was done in each noteworthy commit to this repository.**

<br>

# Commits

## Commit 1:

The first commit was dedicated to adding whitespace to areas where the code seemed a bit cluttered. Doing so made the code much more easy on the eyes.

## Commit 2:

Next, I defined the font-family and a few other properties inside the global selector so that multiple instances of the same styling could be removed. Additionally, there were several properties that were the same but had been targeted through individual selectors. I removed the duplicate code and selected more elements/classes using commas.

## Commit 3:

Commit 3 made 2 small but important changes. 
- The footer contained a copyright symbol which was to the left. I moved it to the right.
- "seo" in the header was not distinguishably different in color for everyone to notice. A slight color change made it more noticeable.

## Commit 4:

This Commit was responsible for helping a new reader identify where the code for the navigation bar coule be found. A class was made and the name of the class indicated exactly what it was for. Making this class also helped make the selector paths more concise for us.

## Commit 5:

Here we found a flaw in the functionality of our webpage. The navigation button for Search engine optimization was not working. Making an id for it solved the problem.

## Commit 6:

Another commit with important changes.
- The header and footer of the webpage were made using div tags instead of actual header and footer tags. We corected that state of affairs.
- The hero image of the webpage was being sourced in the CSS file while all the other images were being sourced in the HTML file. We moved the odd one to the HTML file to make thinsg consistent.

## Commit 7:

Alt descriptions were absent for all images. That problem was taken care of.

## Commit 8:

The paths for some of the selectors were long and not-so-easy to keep a track of. By making more classes, path sizes were made shorter.

## Commit 9:

Once all the major changes had been made to the code, it was time to add comments to the CSS file to explain what was happening in places where there were several style parameters.

<br>

# Refactored code

All major commits have been mentioned above. There were a few others but they were not interesting or significant enough to deserve a mention in this README file. 

The final code files can be found here:

- [HTML](https://github.com/MoeCancode/Code-Refactoring/blob/main/index.html)
- [CSS](https://github.com/MoeCancode/Code-Refactoring/blob/main/assets/css/style.css)

<br>

# Contributors

**Mohammad Abuzar Razvi**

<br>

# License

MIT License

Copyright (c) [2022] [Mohammad Abuzar Razvi]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.



