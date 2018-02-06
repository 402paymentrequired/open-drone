# open-drone
Open hardware drone

## Coding conventions

### Python:
- Use PEP-8. 
- Generally, use double quotes for strings, and single quotes for characters (strings with length 1).
- Try to keep functions at less than 100 lines (preferably 50 lines or less)
- Functions and methods, especially front-facing functions that are part of the API, should contain docstrings formatted according to the NumPy formatting style: https://github.com/numpy/numpy/blob/master/doc/HOWTO_DOCUMENT.rst.txt

### C/C++:
- Header files should contain include guards. The term defined should be the file name in all caps (example_header.h should be #ifndef EXAMPLE_HEADER_H).
- Indent using spaces, four spaces per indent
- Put opening/closing curly braces on their own line
- Keep lines at less than 80 characters wide
- Spaces before and after arithmetic/logical operators; spaces after commas
- At most one blank line at a time inside functions; two blank lines between functions
