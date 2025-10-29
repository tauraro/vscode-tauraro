# Tauraro Language Support

This extension provides comprehensive syntax highlighting and language support for the Tauraro programming language in Visual Studio Code.

## Features

Tauraro is a multilingual programming language that supports both English and Hausa keywords, making programming more accessible to speakers of both languages. This extension provides full syntax highlighting for all Tauraro language constructs.

### Syntax Highlighting

- Full support for English and Hausa keywords
- Highlighting for built-in functions and types
- String interpolation support (f-strings)
- Raw string support (r-strings)
- Byte string support (b-strings)
- Triple-quoted docstrings
- Comments
- Numbers (integers, floats, binary, octal, hexadecimal)
- Operators (arithmetic, assignment, comparison, logical, bitwise)
- Decorators
- Storage modifiers

### Supported Keywords

#### Function and Class Definitions
- `func` / `def` / `aiki` - Function definition
- `class` / `iri` - Class definition

#### Control Flow
- `if` / `idan` - If statement
- `elif` / `kokuma idan` - Else if statement
- `else` / `akasi` - Else statement
- `for` / `duk` - For loop
- `while` / `yayinda` - While loop
- `break` / `tsaya` - Break statement
- `continue` / `cigaba` - Continue statement
- `return` / `maido` - Return statement
- `pass` / `wuce` - Pass statement
- `yield` / `bayar` - Yield statement

#### Exception Handling
- `try` / `gwada` - Try block
- `except` / `catch` / `kama` - Except block
- `finally` / `karshe` - Finally block
- `raise` / `throw` / `jefa` - Raise exception

#### Other Keywords
- `import` / `shigoda` - Import statement
- `from` / `daga` - From statement
- `as` / `dasunan` - Alias
- `with` / `tare` - With statement
- `assert` / `tabbatar` - Assert statement
- `del` / `share` - Delete statement
- `global` / `duniya` - Global variable
- `nonlocal` / `ba_gida` - Nonlocal variable
- `async` / `marasa_jira` - Async function
- `await` / `jira` - Await expression
- `lambda` / `dan_aiki` - Lambda function
- `match` / `daidaita` - Match statement
- `case` / `yanayi` - Case statement
- `in` / `acikin` - Membership test
- `is` / `shine` - Identity test
- `and` / `dakuma` - Logical and
- `or` / `ko` - Logical or
- `not` / `ba` - Logical not

## Requirements

No special requirements. Simply install the extension and open any file with a `.tr`, `.tau`, or `.tauraro` extension.

## Extension Settings

This extension contributes the following settings:

* `tauraro.enable`: Enable/disable Tauraro language support.

Files with the `.tr`, `.tau`, or `.tauraro` extensions will automatically be recognized as Tauraro source files.

## Known Issues

None at this time.

## Release Notes

### 1.0.0

Initial release with full syntax highlighting support for the Tauraro programming language.

---

## About Tauraro

Tauraro is a multilingual programming language that aims to make programming more accessible by supporting both English and Hausa keywords. It combines the simplicity of Python with multilingual support to help non-English speakers learn programming in their native language.

**Enjoy programming in Tauraro!**