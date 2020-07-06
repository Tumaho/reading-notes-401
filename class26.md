## Context

### Context provides a means of passing state down the component tree through a Provider/Consumer relationship.

### In a functional component, you can use the useContext() hook to tap right in.Returns and provides access to whatever your context provider exports

### In a typical React application, data is passed top-down (parent to child) via props, but this can be cumbersome for certain types of props (e.g. locale preference, UI theme) that are required by many components within an application. Context provides a way to share values like these between components without having to explicitly pass a prop through every level of the tree.

## When to Use Context

### Context is designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, theme, or preferred language.