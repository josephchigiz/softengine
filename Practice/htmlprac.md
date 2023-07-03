# <center> HTML BASICS *(w/joe)*<center>
### Intro To HTML
- <> Tags Make up HTML, they are enclosed in these angled brackets
- **Markup Element** - Tags that Contain something within them e.g

````html
<Body>........</Body>
````
- There are also empty elements e.g ````<Br>````
- At the beginning of a html file, we need to put the declaration:
  ````html
  <!doctype html>
  ````
- ...followed by ````<html>```` element.
- The rest of the elements that make up the web page are written within this element.
- ````<head>```` contains important info about the page.
- Here is a snippet example of html code;
````html
<!doctype html>

<html>
    <head>
        <title>My Web Page</title>
    </head>

    <body>


    </body>

</html>
````
- ````<br>```` element is used to add line breaks.
- For extra space between words in a phrase, we use ````&nbsp````

### Lists 
- There are two types of lists
  1. Ordered Lists ````<ol>````
  2. Unordered Lists ````<ul>````
- Both lists have an ````<li>```` element embedded in them.
- Here is an example;
````html
<ul>
  <li>First Item</li>
  <li>Second Itemm</li>
  <li>Third Item</li>
</ul>
````
- Both lists have an ````<li>```` element embedded in them.
### Tables
- ````<table>```` It's the main element and everything is embedded inside it
- ````<tr>```` is the element that identifies it as a table row
- ````<td>```` is the element that contains table data 
- ````<th>```` element identifies it as a column

- My SoftEngine Company offers several services and the timings for these services are offered on my website in the form of this **table**;
````html
        <table>
            <tr>
                <th>Time</th>
                <th>Services Available</th>
                <th>Technician</th>
            </tr>
            <tr>
                <td>11:30 - 12:30</td>
                <td>Repairs</td>
                <td>J.Ochego</td>
            </tr>
            <tr>
                <td>14:00 - 15:00</td>
                <td>One-on-one</td>
                <td>D.Ogweno</td>
            </tr>
            <tr>
                <td>17:00 - 18:00</td>
                <td>Open-Store</td>
                <td>Al.Fonsi</td>
            </tr>
        </table>
````
