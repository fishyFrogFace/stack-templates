# stack-templates
Some stack templates for personal use (my name is in the templates, so change this if you want to use them, unless you want me to have the copyright to your work :p)

## Templates

All templates include a license file and a colored prompt that puts loaded modules on a separate line.

### Unicode
Includes a module that gives you UTF8 support when reading from, appending and writing to files.

### Utils
Includes a module with some useful functions, e.g. strip, ternary operator and split. Here, I put functions I think is missing in base.

### Unicode-Utils
Includes both of the above.

## Installation
You need [Stack](https://www.haskell.org/platform/) to use these templates

## Usage
```
stack new <project-name> fishyfrogface/<template-name>.hsfiles
```
```
cd <project-name>
```
```
stack build
```
```
stack exec <project-name>-exe <path/to/file.txt>
```
