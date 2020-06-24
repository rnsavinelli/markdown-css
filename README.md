# Markdown CSS

A preview of the stylesheet can be found here: https://rnsavinelli.github.io/files/markdown/example.html

See the results of the W3C CSS Validator, for this particular stylesheet, [here](http://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Frnsavinelli.github.io%2Ffiles%2Fmarkdown%2Fmarkdown.css&profile=css3svg&usermedium=all&warning=1&vextwarning=).

![Valid CSS](https://jigsaw.w3.org/css-validator/images/vcss)

## Compilation using Pandoc

### HTML fragment:

First run:
```
pandoc example.md -o example.html
```

Then add this to the top of your HTML file once compiled
```
<link href="/path/to/markdown.css" rel="stylesheet"></link>
```

### Standalone HTML file with CSS:
```
pandoc -s -c markdown.css example.md -o example.html
```

## License

This CSS stylesheet is UNLICENSED.
For more information, visit [http://unlicense.org/](http://unlicense.org/) or see the
[`UNLICENSE`](https://github.com/rnsavinelli/markdown-css/blob/master/UNLICENSE) file.
