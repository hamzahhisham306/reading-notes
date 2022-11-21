# Reading Notes

1. Redux Toolkit
  >> was introduced with a purpose to be the standard way to write redux logic. It is said to be an opinionated, batteries-included toolset for efficient Redux development. By using this, you can write all the code you need for your Redux store in a single file, including actions and reducers. Using this you can make your code more readable. Redux toolkit includes all the tools, you want for a Redux application. At the end of the day all you have is less code and faster setups of Redux in every scenario.


2. What is createSlice in Redux Toolkit?
  >> createSlice is a higher order function that accepts an initial state, an object full of reducer functions and a slice name. It automatically generates action creators and action types that correspond to the reducers and state.
      In Redux-Toolkit, the createSlice method helps us create a slice of the redux-store. This function aims to reduce the boilerplate required to add data to redux in the canonical way. Internally, it uses createAction and createReducer.


3. Why You Should Use Redux Toolkit
  >> Redux Toolkit makes it easier to write good Redux applications and speeds up development, by baking in our recommended best practices, providing good default behaviors, catching mistakes, and allowing you to write simpler code. Redux Toolkit is beneficial to all Redux users regardless of skill level or experience. It can be added at the start of a new project, or used as part of an incremental migration in an existing project.


4. what is the funcion createSlice?
  >> A function that accepts an initial state, an object of reducer functions, and a "slice name", and automatically generates action creators and action types that correspond to the reducers and state.

  >> createSlice accepts a single configuration object parameter, with the following options:

  initialState 
  >> The initial state value for this slice of state.


  name
  >> A string name for this slice of state. Generated action type constants will use this as a prefix.


  reducers
  >> An object containing Redux "case reducer" functions (functions intended to handle a specific action type, equivalent to a single case statement in a switch).

