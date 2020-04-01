---

Muhammad Hussain 02 April 2020

---
# CSS Lists

### Unordered Lists:
- Coffee
- Tea
- Coca Cola
- Coffee
- Tea
- Coca Cola
---

Muhammad Hussain 30 March 2020

---
# CSS border-radius - Specify Each Corner
## The border-radius property can have from one to four values. Here are the rules:

- Four values - border-radius: 15px 50px 30px 5px; (first value applies to top-left corner, second value applies to top-right corner, third value applies to bottom-right corner, and fourth value applies to bottom-left corner): 

- Three values - border-radius: 15px 50px 30px; (first value applies to top-left corner, second value applies to top-right and bottom-left corners, and third value applies to bottom-right corner):

- Two values - border-radius: 15px 50px; (first value applies to top-left and bottom-right corners, and the second value applies to top- right and bottom-left corners):

- One value - border-radius: 15px; (the value applies to all four corners, which are rounded equally:

## Here is the code:

## Example

'''

#rcorners1 {
  border-radius: 15px 50px 30px 5px;
  background: #73AD21;
  padding: 20px;
  width: 200px;
  height: 150px;
}

#rcorners2 {
  border-radius: 15px 50px 30px;
  background: #73AD21;
  padding: 20px;
  width: 200px;
  height: 150px;
}

#rcorners3 {
  border-radius: 15px 50px;
  background: #73AD21;
  padding: 20px;
  width: 200px;
  height: 150px;
}

#rcorners4 {
  border-radius: 15px;
  background: #73AD21;
  padding: 20px;
  width: 200px;
  height: 150px;
}

'''
---

Muhammad Hussain 20 March 2020

---
# How to set text with image in a row
# HTML Code

```html
<div class="class1">
                <img src="anyImage.png" alt="">
                    <div class="class2">
                        <h3>any text</h3>
                        <p>Another text </p>
                    </div>
            </div>
```

# CSS Code
/*Set image Size*/
. class1 img
{
    height: 60px;
    width: 50px;
}

. class1
{
    display: flex;
}

. class2
{
    margin: 0;
    padding: 0;
    display: block;
}


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
- A set of plug-ins that allows the deveople
