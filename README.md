# watch-md

`watch-md` is a small node tool that watches any markdown file for changes and automatically converts it to a PDF when it finds any.
The styling of the generated PDF closely emulates Github Flavored Markdown.

Use it to write your notes quickly in vim, and then make them look pretty.
Comes complete with support for fenced code blocks, nested bullet points, etc.

***Example:***
```
./watch README.md README.pdf
```

## Acknowledgements

This tool was built with help from the [markdown-pdf][1] and the [github-markdown-css][2] projects.

[1]: https://github.com/alanshaw/markdown-pdf
[2]: https://github.com/sindresorhus/github-markdown-css
