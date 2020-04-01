# Markdown CSS

A preview of the stylesheet can be found here: https://rnsavinelli.github.io/files/markdown/example.html

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
