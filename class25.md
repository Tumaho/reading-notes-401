## What are custom hooks?

#### Extract duplicated logic from components,Share common functionality,But not state…,Take advantage of useEffect lifecycle.


#### Unlike a React component, a custom Hook doesn’t need to have a specific signature. We can decide what it takes as arguments, and what, if anything, it should return. In other words, it’s just like a normal function. Its name should always start with use so that you can tell at a glance that the rules of Hooks apply to it.

- Hooks are exported as a function, named as useXXX()

- Hooks return data or behaviors (functions) that are required to reuse their internal functionality

- Hooks are imported into components

- Components can re-use the hook functionality or data/state as needed

- Hooks do not render

## useReducer

### An alternative to useState. Accepts a reducer of type (state, action) => newState, and returns the current state paired with a dispatch method.