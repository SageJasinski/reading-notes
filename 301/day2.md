# Reading notes for class 2

1. Based on the diagram provided the render happens before the componentDidmount happens in the react flow.

2. The first thing that happens in the lifecycle is the Mounting, which includes Constructors, render, componentWillMount.

3. The specific order in which the Mounting happens is as follows: Constructor, static getDerivedStateFromProps, render, componentDidMount.

4. The componentDidMount section is where you would put anything you need to load using a network or initialize the DOM.

5. you can use props to pass what values you want down top the component

6. the difference between states and props is that props are passed from outside the component in, states are handled inside the component

7. We re-render our application via states inside a component

8. We can store anything we want to update once the user has interacted with the component