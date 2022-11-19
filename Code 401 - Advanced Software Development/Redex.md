# Reading Notes

1.  what is the Redux:
  >> Redux provides a solid, stable, and mature solution to managing state in your React application. Through a handful of small, useful patterns, Redux can transform your application from a total mess of confusing and scattered state, into a delightfully organized, easy to understand modern JavaScript powerhouse.


2. what is the Redux rootkit?
  >> Redux Toolkit is our official recommended approach for writing Redux logic. It wraps around the Redux core, and contains packages and functions that we think are essential for building a Redux app. Redux Toolkit builds in our suggested best practices, simplifies most Redux tasks, prevents common mistakes, and makes it easier to write Redux applications


3. whe  we  use Redux?
>> Redux is a valuable tool for organizing your state, but you should also consider whether it's appropriate for your situation. Don't use Redux just because someone said you should - take some time to understand the potential benefits and tradeoffs of using it.
Here are some suggestions on when it makes sense to use Redux:
You have reasonable amounts of data changing over time
You need a single source of truth for your state
You find that keeping all your state in a top-level component is no longer sufficient

4. Redux benefits:
   - You have large amounts of application state that are needed in many places in the app
   - The app state is updated frequently over time
   - The logic to update that state may be complex
   - The app has a medium or large-sized codebase, and might be worked on by many people
