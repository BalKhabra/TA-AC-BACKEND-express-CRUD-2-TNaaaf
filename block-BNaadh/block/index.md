writeCode

Q. Write an express generator command with varying options to generate an express app with the following features:

- using ejs as template engine
express --view=ejs sample

- no views for express application
express --view=no-view sample

- express app with gitignore
express --view=no-view sample

- express app with sass support for styling.
express --css=sass sample

- ejs as template engine and sass for styling
express --view=ejs --css=sass sample

- pug as template engine and gitignore together
express --view=pug --css=sass sample
