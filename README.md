# God-Golang
go version go1.19 darwin/amd64

## Should to know:
- Simple command-line routines
- Web-based applications
- Systems programming

## Knowledge
- Go is a compiled, statically typed language
- The Go tool can run a file without precompiling
- Compiled executables are OS specific
- Compiled apps contain a statically linked runtime
- No external virtual machine is needed

- Go has some object-oriented features
    * Define custom interfaces
    * Custom types can implement one or more interfaces
    * Custom types can have member methods
    * Custom structs (data structures) can have member fields

- Go doesn't support:
    * Type inheritance (no classses)
    * Method or operator overloading
    * Structured exception handling
    * Implicit numeric conversions

- Acestor Languages
    * Go is designed as a next-generation language for C
    * Borrows some syntax from C
    * Borrows from the family of Pascal, Modula, and Oberon languages
    * Go tries to reduce the amount of typing

## Basic Go syntax

### Essential Syntax Rules
- Go is case sensitive
- Variable and package names are lowercase and mixed case
- Names of public fields have initial uppercase characters
- Initial uppercase character means the symbol is exported

- Semicolons Usually Not Needed
    * Line feed ends a statement; no semicolon required
    * Semicolons are part of the formal language spec
    * The lexer adds them as needed

- Code Blocks with Braces
    * Code blocks are wrapped in braces
    * Starting brace on same line as preceding statement

- Built-In functions, members of built-in package:
    * len(string) - returns the length of the string
    * panic(error) - stop execution; displays error message
    * recover(error) - manages behavior of a panicking goroutine
    
