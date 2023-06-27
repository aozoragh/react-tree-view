"# react-tree-view"
Use the value of the toggled prop to determine the initial state of the content (collapsed/expanded).
Use the useState() hook to create the isToggled state variable and give it the value of the toggled prop initially.
Render a <span> element and bind its onClick event to alter the component's isToggled state.
Determine the appearance of the component, based on isParentToggled, isToggled, name and checking for Array.isArray() on data.
For each child in data, determine if it is an object or array and recursively render a sub-tree or a text element with the appropriate style.
