# Mathpad

Mathpad is a small extension for [Visual Studio Code] that turns a Markdown editor into an interactive scratchpad calculator.

[![License](https://img.shields.io/github/license/sagebind/mathpad)](LICENSE)
[![Visual Studio Marketplace Version](https://img.shields.io/visual-studio-marketplace/v/sagebind.mathpad)](https://marketplace.visualstudio.com/items?itemName=sagebind.mathpad)
![Visual Studio Marketplace Installs](https://img.shields.io/visual-studio-marketplace/i/sagebind.mathpad)
[![GitHub Workflow Status](https://img.shields.io/github/workflow/status/sagebind/mathpad/build)](https://github.com/sagebind/mathpad/actions)

I created this because I couldn't find a good notebook calculator that I liked that

- is free and open source,
- supports all the platforms I care about,
- works completely offline,
- supports variables and functions,
- allows you to edit anywhere (as opposed to REPL style),
- and works in and saves as plain text.

I already have [Visual Studio Code] installed on all my computers and use it for lots of text editing purposes, so I decided to make it also my calculator using this extension.

## Features

- Math expressions on their own line inside a Markdown editor are evaluated automatically and their results are displayed in grey at the end of the line.
- Variables can be defined on their own line like `x = 42` and referenced on any line below it.
- Functions can be defined on their own line like `f(x) = 42 / x` and referenced on any line below it.
- Changing a variable or function definition will automatically re-evaluate everywhere it is used in the rest of the document.

Much more is available as math expressions, which are powered by [Math.js]. Check out the Math.js documentation for even more examples of what sorts of expressions can be evaluated.

## Future ideas

There's a lot more neat ideas that _could_ be implemented, including:

- Defining our own language/editor type with dedicated math syntax highlighting.
- Evaluating expressions embedded in normal text.
- Replacing an expression with its result.

## License

This project's source code and documentation is licensed under the MIT license. See the [LICENSE](LICENSE) file for details.


[Math.js]: https://mathjs.org
[Visual Studio Code]: https://code.visualstudio.com
