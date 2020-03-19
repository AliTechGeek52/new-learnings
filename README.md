---

Muhammad Hussain 19 March 2020

---

# Use CSS. this removes underlines from a and u elements:

a, u {
    text-decoration: none;
}

# This will remove your colour as well as the underline that anchor tag exists with

a {
     text-decoration: none ;
  }
a:hover
  {
    color:white;
    text-decoration:none;
    cursor:pointer;
   }


---

Muhammad Hussain 18 March 2020

---

# CSS :hover Selector

### Example
### Select and style a link when you mouse over it:

a:hover {
  background-color: yellow;
}

### Definition and Usage
The :hover selector is used to select elements when you mouse over them.

**Tip:** The :hover selector can be used on all elements, not only on links.

**Tip:** Use the :link selector to style links to unvisited pages, the :visited selector to style links to visited pages, and the :active selector to style the active link.

**Note:** :hover MUST come after :link and :visited (if they are present) in the CSS definition, in order to be effective! nad :hover not works if any space given between hover and id or variable


# Fast HTML by emmet
### What is emmet?
- A set of plug-ins that allows the deveopler for high speed coding.
- Basically it expends the abbreviations.
- Emmet is supported in html, css, scss, less, stylus, xml, xsl, haml, jade, slim, jxs and also any language that inherits from any of the above like handlebars and php.
- In Visual Studio Code emmet is enables by default.
- Emmet supported in these [editors](http://emmet.io/download/)
### Example
#### HTML
write ul>li*3>div.hello then hit tab

    <ul>
        <li>
            <div class="hello"></div>
        </li>
        <li>
            <div class="hello"></div>
        </li>
        <li>
            <div class="hello"></div>
        </li>
    </ul> 

#### CSS
write m10 then hit tab

    margin: 10px;
write p20 then hit tab

    padding: 20px;

#### for further [reference](https://docs.emmet.io/)
---

Muhammad Umer 8Feb20 12:19 hours

---
# Shourtcut keys in VS
We can use shortcut keys to code fast. Some of the shortcut keys are :
- |Alt| + |Arrow Down| (Use move the current line to up/down). 
- |Shift| + |Alt| + Arrow up/down (Use to copy the line).
- |Shift| + |!| then press enter (Basic code for html).
- |Ctrl|+|X| or |Shift|+|Delete| (Cuts the currently selected item to the clipboard).
- |Ctrl|+|C| or |Ctrl|+|Insert| (Copies the currently selected item to the clipboard).
- |Ctrl|+|V| or |Shift|+|Insert| (Pastes the item in the clipboard at the cursor).
- |Ctrl|+|Z| or |Alt|+|Backspace| (Undo previous editing action).
---

Maaz Ahmed (Boi) 13Feb20 07:22PM

---
# My Learning :
- Free code camp completed.
- https://bennettfeely.com/clippy/ (to make different shapes through clip-path property).
- flexbox and grid completed.
---

Faheem  14Feb20 07:22PM

---
# Alligator.io icons:

🤹  🏆  ⚡ ↓
---

Maaz Ahmed (Boi) 14Feb20 07:22PM

---

# clip
The clip CSS property defines what portion of an element is visible. The clip property applies only to absolutely positioned elements, that is elements with position:absolute or position:fixed .

clip: rect(110px, 160px, 170px, 60px); 
values descript a top/left point and bottom/right point

# clip-path
The clip-path property in CSS allows you to specify a specific region of an element to display, rather than showing the complete area.

clip-path: inset(10px 20px 30px 40px);
values are from-top, from-right, from-bottom, from-left

---

Maaz Ahmed (Boi) 15Feb20 04:10PM

---

# Update pre-built repo in github:
#### Following are the steps :
- Open gitbash from desktop.
- Type "git clone" and then paste url of that repo.
- Open cloned(downloaded) folder.
- Put files, want to push.
- Type "git add ."  
- Type "git commit -m [meaningful message]".
- Type "git push".

---

Maaz Ahmed (Boi) 16Feb20 04:20AM

---

# To Create a new Repository on GitHub:
##### First of all why we create repositories of github?
**Ans:** You can store a variety of projects in GitHub repositories, including open source projects. With open source projects, you can share code to make better, more reliable software.
To put your project up on GitHub, you'll need to create a repository for it to live in.

## Steps to create a Repository on GitHub:
1. In the upper-right corner of any page, use the + drop-down menu, and select New repository.
2. Type a short, memorable name for your repository. For example, "hello-world".
3. Optionally, add a description of your repository. For example, "My first repository on GitHub."
4. Choose a repository visbility. For more information, see "[About repository visibility.](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/about-repository-visibility)"
5. Select Initialize this repository with a **README**.
6. Click Create repository.

Congratulations! You've successfully created your first repository, and initialized it with a *README* file.

---

Rafay Hasan Khan 17Feb20 02:07AM

---
- # update link
- always update link in your repository's Readme file as others can easily visit your website through that link 
---
Faheem

---
# Correction in Faheem's learning about github pages
- You don't have to update your link, when you push your code github pages link automatically updated by its own.
- Put your github pages in your repo's description, this will me more easy to navigate to the page.
---
Muhammad Umer 17-feb-2020 9:20 PM

# Programming with R
- It is the language of data science
- According to the survey of data mining experts R is on the top
- R is 50% more efficient than Python
- It is free and open source
- R is optimize for vector operations (those operations are used to move exact row without an loops)
- R has a great community
- R has 9000+ contributed or 3rd party packages
## Packages
- Bundle of code that adds new feature to R
- There are two types of packages
  1. Base packages
  2. Contributed packages
    ### Base Packages
    - Installed in R but not loaded by default
    ### Contributed Packages
    - Need to be downloaded,installed and loaded spreatly
## Resources to find packages
1. CRAN (Comprehansive R archive network)
2. Crantastic
3. github.com/trending/r
    ### CRAN
    - It is the official website to download R packages
    ### Crantastic 
    - It contains most popular and recent packages
    ### github.com/trending/r
    - A github repo where you can clone the desired packages
## Packages mostly used
1. dplyr (used for manipulating data frames)
2. tidyr (used for clearing up the information)
3. stringer (used for wording with strings/texts)
4. lubridare (used for manipulating date information)
5. httr (used for working with web data)
6. ggvis (used for grammar graphics visualization)
7. ggplot2 (A popular package for creating graphics or data visualization)
8. shing (used for creating interactive apps that can be installed in websites)
9. rio (It stands for R input/output, used for importing/exporting of data)
10. rmarkdown (used for interactive notebooks & rich documents)
11. pacman (It stands for R package manager)
## Package installation command
install.package("package name") then hit command/ctrl + enter
require(package name) it gives a confirmation message
library(package name) it don't give a confirmation message
## Basic Graphics
#### plot command
- plot()
 used for basic x-y graph ploting
#### help command
- ?plot
#### Bar charts
- These are the basic graphics for basic data
#### Histrogram 
- It is used for data that is quantitative, scaled, measured on interval or ratio level. It consists of four characteristics
    1. Shapes
    2. Gaps
    3. Outliers
    4. Symmetry
#### Scatter plots
- Visualization the association between two quantative variables, following are the characteristics of scatter plots
  1. Linear
  2. Spread
  3. Outliners
  4. Correlation
#### Overlaying Plots
- It is used to increased information density
## Basic Statistics
#### Summary
- It is used to get some precision (numerical information)
- It is used for counting the categories
- It is used for quartiles and mean for quantitative variables
#### Describe
- It is used to get some more details
- It comes from psych package
- This comes after graphical summary
## Accessing Data
#### Data formats
- Data types (int, char, logical complex, raw, etc)
- Data structures (vector, matrix, array, data frame, list)
#### Vector
- It consists of 1+ numbers
- It is 1D array
- All elements should have same data types
- It is R basic data object
#### Matrix
- It consists of 2D 
- It has same length 
- It consists of same data classes
- Column not named
#### Array
- Identical to array but it has 3+ dimentions
#### Data frame
- It contains vectors of multiple types
- It has same length
- It is closest R analoge to spreadsheet
- It has some special functions
#### List
- It is most flexible
- It has ordered collection of elements
- Any class of length or structure
- A list can include many lists
## Coercion
- Changing data object from one type to another
## Factors
- An attribute of a vector that specifies the possible values and their order
- It has a given opportunity to assign labels to your variables and use them as factors in various analysis if you do experimental research so this becomes really important
## Entering Data
#### Methods
- colon
- seq (sequence)
- c (concatenation)
- scan
- rep (repetition)
- <- assignment operators
#### Importing Data
- Kinds of data files
    1. CSV (comma-separated values)
       - Plain text version of spreadsheets
    2. Txt
    3. XLSX (MS Excel spreadsheet)
    4. JSON (JavaScript object notation)
- R has many functions for importing data in many formats. rio package is used for this purpose
#### Modeling Data
- Hierarchical clustering
## Principal Components
- less = more
- less noise and fewer unhelpful variables in data = more meaning AKA dimensionality reduction
#### PCA
- It stands for principal component analysis
- Two variables
- Perpendicular distance
- Collapse
- Rotate 
- It converts 2D to 1D but maintained most important information
## Regression
- Out of many variables only one variable
- Use many variables to predict scores on one variable 

### [Set up R](https://github.com/MuhammadUmer0/Programming-with-R)
### [R documentation](https://www.r-project.org/other-docs.html)
---
Muhammad Umer 21Feb2020 5:43 PM


## How to open "FindBox" in pc?

- you can open the find box in your pc by the given shortkey (CTRL + f).


-------------------------------------
# Python List vs. Tuples
Lists and Tuples store one or more objects or values in a specific order. The objects stored in a list or tuple can be of any type including the nothing type defined by the None Keyword.
### Syntax Differences
Syntax of list and tuple is slightly different. Lists are surrounded by square brackets [] and Tuples are surrounded by parenthesis ().

#### Example 1.1: Creating List vs. Creating Tuple
list_num = [1,2,3,4]
tup_num = (1,2,3,4)

print(list_num)
print(tup_num)
#### Output:

[1,2,3,4]
(1,2,3,4)
Above, we defined a variable called list_num which hold a list of numbers from 1 to 4.The list is surrounded by brackets []. Also, we defined a variable tup_num; which contains a tuple of number from 1 to 4. The tuple is surrounded by parenthesis ().

In python we have type() function which gives the type of object created.

#### Example 1.2: Find type of data structure using type() function
type(list_num)
type(tup_num)
#### Output:

list
tuple
---

Maaz Ahmed (Boi) 17Mar20 02:20AM

---
