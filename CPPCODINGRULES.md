### Does the code do what is expected?

- Does the code fully implement the functional specification?
- Does the code respect the technical requirements?
- Does the code include unit tests?
- Does the code include logs?

### Does the code follow C++ standards and best practices?

- Are the #includes complete?
- Are the variables and parameters well initialized? 
- Are the variables and parameters declared in their scope of use?
- Do the functions have a correct format (values/reference, parameters, no return to a local object)
- Do all strings use the std::string class, use the right functions and member operators?
- Are the pointers well initialized ? deleted after use ? Not deleted before creation?
- Are the {}s properly paired?
- Does each class implement a Constructor, Destructor and a Copy Operator?
- Is the #define used appropriately?
- Do the loops use iterators when possible?

### Is the code readable?

- Does the code follow the C++ style guide? ([Google C++ Style Guide](https://google.github.io/styleguide/cppguide.html))
- Is the number of characters per line <= 80 (reasonable limit)?
- Is the code well indented?
- Is the code well commented?
- Does the code respect the DRY (Don't Repeat Yourself) principle?
- Are the names of functions, variables, class names, etc. clear?
- Is the code well grouped in elementary functions, i.e. no code duplication?
- Is the naming consistent throughout the code?

### Is the code documented?

- Is there a documentation of the code?
- Do the comment blocks respect the Doxygen syntax? (Doxygen Manual: Documenting the code)
- Do the comments explain the why and not the how?
