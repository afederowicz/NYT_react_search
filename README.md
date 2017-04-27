# NYT_react_search
react hw

Props in react are parameters that can be used to customize components, which are designated when the component is created. Props are set by the parents and are fixed throughout the lifetime of the component. An example would be a light switch that is painted red and is permanently red for the duration of its lifespan.

States in react are are the current status of whatever component you are trying to define. Unlike props, state is used to define the current state of the component - you are also able to change the current state of a component to fit a specific situation, such as a light switch being classified as on or off.

The component lifecycles in react are comprised of several methods - things with the prefix of "will" are called right before something happens, and the previx of "did" are called right after something happens.
The three main lifecycles are mounting, updating, and unmounting. Mounting is called when an instance of a component is being created and instered into the DOM. Updating is called when a component is being re-rendered, or updated. Go figure. Unmounting is called when a component is being removed from teh DOM.