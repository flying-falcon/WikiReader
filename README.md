# WikiReader

## About
The application is a [REPL](https://en.wikipedia.org/wiki/Read-eval-print_loop) that accepts the following commands
1. READ <article>
2. QUIT
3. HELP
4. ABOUT <article>
5. RANDOM

## How to run
To initialise the app run 
`node read_wiki.js -l en` this will bring up https://en.wikipedia.org/wiki/ environment.
Once initialised user can enter these commands.
```
1. READ <article>
2. QUIT
3. HELP
4. ABOUT <article>
5. RANDOM
```

## Usage

```Usage: read_wiki [options]

Options:
  -l, --language <type>  Select Language
  -h, --help             output usage information
```
* use -l to select language

### 1. READ &lt;article&gt; usage :

***Note: Article must be unique.***

Prints the unique article text one paragraph at a time, waiting for the user to press a key before printing the next
paragraph. It is a plain text, not wikitext markup or HTML. It prints the
text on paragraph at a time, waiting for the user to press a key before printing the next
paragraph. The user will be able to stop reading an article with a special key ( _**s and then press/return enter on keyboard**_ ).

### 2. QUIT usage :
To exit the application type QUIT ( _**and then press enter/return on keyboard**_ ).

### 3. HELP usage :
Print the available commands with a short description. Type HELP ( _**and then press enter/return on keyboard**_ ).

### 4. ABOUT &lt;article&gt; usage :
Shows metadata about an article. Type HELP ( _**and then press enter/return on keyboard**_ ).

### 5. RANDOM usage:
Prints the unique random article text.

