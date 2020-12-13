# htmail_parser

This is a small email making utility that reads html with classes, and turns it into C# StringBuilder syntax (that will eventually create email). Since most email clients support only inline styles, this utility also automatically converts provided classes to inline styles, and escapes double quotes characters. Variables are also supported, as well as C# expressions, but to be fair, it looks ugly as hell :P

![Alt text](/src/htmail_parser_preview.png?raw=true "Preview")
