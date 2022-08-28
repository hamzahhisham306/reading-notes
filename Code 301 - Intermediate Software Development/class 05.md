# Reading Notes
# I have to understand these terms well in order to understand the way the library works and how to build web pages well


1. What is the single responsibility principle and how does it apply to components?
  > According to the SRP, each function or class should be limited to doing a single task; if it turns out that it does many tasks,
  >  it must be divided into smaller functions. the components tree is the same.
  
2. What does it mean to build a ‘static’ version of your application?
  > it is means bulid a page without functionality.
  
3. Once you have a static application, what do you need to add?
  > we have to know what we need to do with my application and  add function to my application.
  
4. What are the three questions you can ask to determine if something is state?
   - Can state be any kind of data?
   - Can change state when anothere componetns?
   - can we use another way to declare state?
    
5. How can you identify where state needs to live?
  >  For each piece of state in your application:

  -Identify every component that renders something based on that state.
  -Find a common owner component (a single component above all the components that need the state in the hierarchy).
  -Either the common owner or another component higher up in the hierarchy should own the state.
  -If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.

6. What is a “higher-order function”?.
 > function that operate on other functions, either by taking them as arguments or by returning them, are called higher-order functions.
 > higher-order functions allow us to abstract over actions, not just values. They come in several forms.

7. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
 > In order to compare two values and return a boolean result, it calls the arrow function.
8. Explain how either map or reduce operates, with regards to higher-order functions.
  > map function return new array without remove anything from it but make some changing.
  > reduce function return new array with remove some element form array it is depend about conditions.



## Things I want to know more about
