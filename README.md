# Markdown CSS

This is a simple style with normalized defaults, it should work on anything from a desktop, to a phone.

View the live preview here: http://simon.lc/sites/markdown/.

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
