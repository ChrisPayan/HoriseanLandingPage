# HoriseanLandingPage
```
The main purpose of this project was too refactor some of the CSS and HTML to make the website more user accessible and easier to work on.

Ive highlighted some of the changes to showcase where improvement were made.
```
# Header

## Important Refactoring in CSS

```CSS
nav {
    float: right;
    padding-top: 15px;
    padding: 20px;
    background-color: #2a607c;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}
```

```
The Div's that were controlling the NavBar were complied and replace with a single Nav tag that controls the format of the listed items.
```


# Body

## Important Refactoring and changes in HTML

```HTML
<!-- Added an ID for search engine optimization -->
 <section id="search-engine-optimization" class="search-engine-optimization">
```
```
To fix the issue with the navbar an ID "id="search-engine-optimization" was created.
```

## Important Refactoring in CSS

```CSS
/* Combined all 3 formatting into one */
.benefit-lead, .benefit-brand, .benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
    margin-bottom: 10px;
    text-align: center;
}

```
```
Similar technics were use all over the CSS code to reduce lines of code without changing the overall project.
```

## Contributing
To hdezbriant

Please make sure to update tests as appropriate.

## License
