# HTML-Crash-Course

***

## Requirements:
- Web Browser: Firefox
- Text Editor: Visual Studio Code

***

## Definitions
HTML - Hyper Text Markup Language
Root page is called index.html
| | |
| - | - |
| Inline Elements | Block Elements |
| Do not start on a new line | Start on a new line |
| Take only the necessary width | Take full width available |
| strong, em, a, label, input | div |
***

## HTML Page Structure
```html
<!DOCTYPE html>
<html>
    <head>
        <title> The title will appear in the browser's page tab. </title>
    </head>
    <body> Content that needs displaying </body>
</html>
```

***

## Tag Syntax
```html
<tagname> Content </tagname>

<!-- This is a comment >

<!-- Headings -->
<h1> Heading 1 </h1>
<h2> Heading 2 </h2>
<h3> Heading 3 </h3>
<h4> Heading 4 </h4>
<h5> Heading 5 </h5>
<h6> Heading 6 </h6>

<p> Paragraph </p>

<br> -> line brake

<strong> Text is by default bold, but can be changed with css. </strong>

<em> Text is by default italic, but can be changed with css. </em>

<a href="https://google.com" target="_blank">This is a link, with target set to _blank -> opens a new tab.</a>

<ul>
    <li> Bullet </li>
    <li> point </li>
    <li> list </li>
</ul>

<ol>
    <li> Ordered </li>
    <li> list </li>
</ol>

<table>
    <thead>
        <tr> --> Table row
            <th>Name</th> --> Table heading
            <th>Email</th>
            <th>Age</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Fuzz</td> --> Table data
            <td>fuzz@gmail.com</td>
            <td>22</td>
        </tr>
    </tbody>
</table>

<form action="" method="POST"> --> Form;
    <label for="" placeholder="A text placeholder"> This is a label </label>
    <input type="text" name="first-name" id=""> --> There are many types of inputs!

    <div>
        <label for=""> Email </label>
        <input type="email" name="email" id=""> --> Specifying the emai type adds email validation when submitting the form!
    </div>

    <div>
        <label for=""> Message </label>
        <textarea name="message" id="" cols="30" rows="10"></textarea> --> For larger messages
    </div>

    <div>
        <label for=""> Gender </label>
        <select name="gender" id=""> --> Selection list
            <option value="male"> Male </option> --> Option 1
            <option value="female"> Female </option> --> Option 2
            <option value="other"> Other</option>
        </select>
    </div>

    <div>
        <label for=""> Age </label>
        <input type="number" name="age" id=""> --> For numbers
    </div>

    <div>
        <label for=""> Birthday </label>
        <input type="date" name="birthday" id=""> --> Date picker
    </div>

    <input type="submit" name="submit" value="Submit"> --> Submit button

</form>

<hr> -> a horizontal line

 <!-- Buttons -->
<button>Click Me</button> 

<!-- Images -->
<img src="london.png" alt="London"> --> Image' source + its description

<!-- Quotations -->
<blockquote cite="http://the_cited_text.com">
    Some quote
</blockquote>

<p> The <abbr title="World Wide Web">WWW </abbr> is awesome. </p> --> when hovering the WWW text, a label around it will display World Wide Web

<p>HTML <cite>crash</cite> course</p> --> It is a tradition to let the browser where you cite

<small> Posted by ClaoMike </small> --> By default, it makes the text smaller

```

## Semantic Tags
Useful for diving the webpage into separate sections.
```html
<header></header>

<nav></nav> --> The navigation bar

<section></section>

<article></article>

<aside></aside> -> Side bar content

<footer></footer> --> the content at the end of the page

<details></details>

<main></main>
```