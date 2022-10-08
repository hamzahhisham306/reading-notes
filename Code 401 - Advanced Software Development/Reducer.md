
1. How can we ensure that an effect hook runs only once?
 > Side Effect Runs Only Once After Initial Render
You can pass an empty array as the second argument to the useEffect hook to tackle this use case. useEffect(() => { // Side Effect }, []); In this case, the side effect runs only once after the initial render of the component

2. Can useState() update more than one state variable at the same time?
 > yes we can by make first  spread operator(...) for state then name what you need to change.

3. Is useState() synchronous? 
  No it is, it is an asynchronous hook and it doesn't change the state immediately, it has to wait for the component to re-render.
  

