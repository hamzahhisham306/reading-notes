# Note 2
# **I have to understand these terms well in order to understand the way the library works and how to build web pages well**

1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
The first render cycle is crucial in an isomorphic software. Here, you'll use lifecycle events to regulate the environment in which code executes. 
Because they depend on the window object, some third-party libraries, for instance, cannot be loaded or used on the server.
Additionally, you might want to provide some unique scroll behavior on the window event. By integrating with the numerous lifecycle methods made available 
on the initial render,you will need to take charge of this.

2. What is the very first thing to happen in the lifecycle of React?
mounting:An instance of a component is created and injected into the dom during the mounting process.

3. What does componentDidMount do?
method is called after the component is rendered. This is where you run statements that requires that the component is already placed in the dom.

4. What types of things can you pass in the props?
With the use of props, you may transfer values up and down the component tree. It was only a string variable in the prior example. However, props can be any 
JavaScript data type, including arrays, objects, and integers.


5. What is the big difference between props and state?
- state :is a structure that may be updated. A component's status could change over time. A component is made dynamic and interactive by the state, 
  which is used to store data or information about the component. Stateful components have their own state, while stateless components don't.
  The former are referred to as having no state at all.
  
- props: are read-only parts that provide a mechanism to transfer data from one part to another. It keeps track of a tag's attribute values. 
  It functions similarly to HTML attributes because it is an immutable object. Since the props are immutable, they cannot be changed 
  from within the component. But inside the components, we may add properties, often known as props. Thus, immutable data is added to the component via the props.
  
  6. When do we re-render our application?
   when we need to change content or update date.
   
  7. What are some examples of things that we could store in state?
    it could be array to store something or it could be number to be counter for something.
    
    
    ## Things I want to know more abo
