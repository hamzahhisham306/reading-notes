# Reading Notes

# To properly understand how the library operates and how to create web pages, I need to fully comprehend these phrases.


1. What is functional programming?
  > Functional programming is a programming paradigm a style of building the structure and elements of computer programs that treats computation as the evaluation of
  >  mathematical functions and avoids changing-state and mutable data
What is a pure function and how do we know if something is a pure function?
 >  It returns the same result if given the same arguments
 >  all operations performed in pure functions are not affected by their state. As a result, the same input parameters will give the same deterministic 
 >  output regardless of how many times you run the function.
What are the benefits of a pure function?
1. It is easier to use and test
2. Pure functions operate independently and produce the same results for the same inputs.
What is immutability?
> Its state is immutable once it is generated, incapable of changing over time.
What is Referential transparency?
> A pure function that will always have the same output, given the same input.
> pure functions + immutable data = referential transparency


1. What is a module?
 > Modules are the blocks of encapsulated code that communicates with an external application on the basis of their related functionality.
2. What does the word ‘require’ do?
 > s a built-in function to include external modules that exist in separate files. require() statement basically reads a JavaScript file,
 >  executes it, and then proceeds to return the export object
3. How do we bring another module into the file the we are working in?
 > We utilize the require method in the file we're working on and enter the path to the other module after going to the module we want to bring and writing module.exports = method name 
4. What do we have to do to make a module available?
   npm install + name module

## Things I want to know more about,
