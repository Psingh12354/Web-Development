# Web-Development
Here I have uploaded all my Web Development related stuff which i have been used or implemented on VSCode

![](https://github.com/Psingh12354/Web-Development/blob/master/imp.PNG)

In this image content width=deveice width meanse it tells about making your site side adjustable

ie=edge foe internet explorer

name=description represent the description which you can use to maintaint the traffic
name=keyword which highlight some particular keyword to maintain the traffic.
use **robots** noindex and nofollow when you don't want to gather traffic through search engine

- **strong** to bold
- **em** to emphasized or italiq
- **hr** to create a horizontal line


**Press Alt + position** to add on multiple places at once

press **target="blank"** in anchor tag to open a site in new tab

use **ol** and **ul**
in **ol**  use **type** command to denote the type of order
can add ultiple list

**table** can be made by using table and tablehead and tablebody **thead and tbody**

## Today Code

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <a href="https://google.com" target="blank">Google</a><br>
    <a href="https://facebook.com" target="blank">Facebook</a><br>
    <a href="/aboutus.html" target="blank">NEw</a>
    <img src="https://source.unsplash.com/random" alt="If not loaded">
    <ul>
        <li>Lorem ipsum dolor sit amet consectetur adipisicing elit. Volupt.</li>
        <li>Lorem ipsum dolor sit amet consectetur adipisicing elit. Placeat, nulla!</li>
    </ul>
    <ol type="a">
        <li>Lorem ipsum dolor sit amet consectetur adipisicing elit. Culpa, dolore?</li>
        <li>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Et, debitis.</li>
    </ol>
    <table>
        <thead>
            <tr>
                <th>Name</th>
                <th>Age</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Priyanshu</td>
                <td>20</td>
            </tr>
            <tr>
                <td>Priyanshu</td>
                <td>20</td>
            </tr>
            <tr>
                <td>Priyanshu</td>
                <td>20</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
```

## Form

Use **form** to store the backend value like php
Press **Alt+select+ arrow key** to move the whole file at once

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>Form</h1>
    <!--form is use to store all the backend data like php -->
    <form action="backend.php">
        <!-- use label tag to select a entry box by clicking on name and add it in id of input -->
        <label for="name">Name</label>
        <div>
         <input type="text" name="myName" id="name">
        </div>
        <br>
        <div>
            Role: <input type="text" name="myRole">
        </div>
        <br>
        <div>
            Email: <input type="email" name="myEmail">
        </div>
        <br>
   
        <div>
            <input type="datetime" name="" >
        </div>
        <div>
            Date:  <input type="date" name="">
        </div>
        <div>
            <input type="number" name="" id="">
        </div>
        <div>
            Are you eligible? : <input type="checkbox" name="MyEligibility" id="">
        </div>
        <!-- Use same name in radio show to make one check at a time -->
        <div>
            Gender: Male <input type="radio" name="myGender" id=""> Female <input type="radio" name="myGender" id="">
        </div>
        <div>
           Write About yourself : <br> <textarea name="myText" cols="30" rows="10"></textarea>
        </div>
        <!-- make a selection box using select  use selected for bydefault-->
        <div>
            <label for="car">Car</label>
            <select name="myCar" id="car">
            <option value="ind" selected>Indica</option>
            <option value="swf">Swift</option>
        </select>
        </div>
        <div>
            <input type="submit" value="Submit Now">
            <input type="reset" value="Reset Now"> <!-- To reset the value -->
        </div>
        <div></div>
    </form>
</body>
</html>
```

## Inline & Block Element

**p** is block element which means it take whole row wise space 
**span** to make a **p** in one line
**span** is block element
**strong** and **achor** is inline element
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Inline & Block Element</title>
</head>
<body>
    <p style="border: 2px solid red;">This is a paragraph</p>
    <p style="border: 2px solid red;">This is another paragraph</p>
    <span style="border: 2px solid red;">This is a span</span> <span style="border: 2px solid red;">This is another span</span>
    <strong style="border: 2px solid red;">This is strong</strong>
    <a href="" style="border: 2px solid red;">hello</a>
</body>
</html>
```
### Class & id

Id is unique while class can be multiple
. for class 
for id #
use **emmet* for faster coding
### span.redBG

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Classes in HTML</title>
</head>
<body>
    <h3>Ids and classes in htmml</h3>
  <div id="mainbox" class="redbg">   <!-- id is identifier -->
this is mainbox
    </div>
    <span class="redbg"></span>
    <span class="redBG"></span>
</body>
</html>
```
### Html Entities

&nbsp non breaping space
use to write special character
check html entites on google

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Entities</title>
</head>
<body>
    <div class="container">
        <p>this is paragraph</p>
    </div>
    <div class="container">
        <p>this is &nbsp; &nbsp; paragraph</p>
        <p>paragraph is written like this &lt;p&gt; </p>
        <p>pound &pound;</p>
        <p>copywrigth &copy;</p>
        <p>fraction is writtent like this &frac12;</p>
        <p>Empty charater &#8203;&#8203;</p>
    </div>
</body>
</html>
```
### span#mainSpan

### semantic 

it is use to tell google for what purpose you have use any kind of tags like a header or navigation bar to define which is nav
check semantic element for further knowledge
non-semantic-: div,span

## CSS(cascading style sheet)

Types of CSS:
(1) Inline
(2) Internal
(3) External

Inline CSS have higher priority but use of external and internal prefer
use **!important** to give a part of code higher priority
