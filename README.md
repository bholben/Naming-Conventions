Naming Conventions
==================

## Lingo & Usage
This is a brief summary of programming naming conventions and notes about how I use them.

### snake_case
* lower_snake_case -- filenames, Python variable / function names
* Upper_Snake_Case
* SCREAMING_SNAKE_CASE -- Python constant names
* _private_snake_case -- Python private variable / function names
* \__dunder\__ (*aka \__double_underscore\__*) -- Python reserved names

**Default:** When someone says snake case, they are commonly referring to lower snake case.
 
### spinal-case
*aka kebab-case, lisp-case, caterpillar-case*  
* lower-spinal-case -- Javascript filenames, CSS class / id names  
* Train-Case  

**Default:** When someone says spinal case, they are commonly referring to lower spinal case.

### camelCase
* lowerCamelCase -- Javascript variable / function / attribute names  
* UpperCamelCase (aka StudlyCaps) -- Python class / exception names, Javascript constructor funtion names

**Default:** When someone says camel case, they are commonly referring to lower camel case.

### compactcase
I don't know of a commonly used word to describe this word compression technique.  
* lowercompactcase  
* UPPERCOMPACTCASE -- Javascript global variables

## Filenaming

### Python, YAML
**Filetypes:** _*.py, *.yaml, *.yml_  
**Convention:** snake_case.py  

### Web development, JSON
**Filetypes:** _*.html, *.css, *.js, *.json, *.jade, *.scss, *.sass, *.less, *.styl_  
**Convention:** file-name.plugin-name-ver.sion.min.ext  
* filename.ext is the core, all other elements optional
* All lower case - no camelCase (universal compatibility)
* Scarce or no underscore usage
* Push two words together if easy to read, i.e. scrollspy.js

### ALLCAPS
README.md  
LICENSE  

