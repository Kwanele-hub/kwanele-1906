---
layout: post
type: "Ract props"
date: 2021-02-25
---
## React props

Props are arguments passed into React components. They  are passed to components via HTML attributes.
React Props are like function arguments in JavaScript and attributes in HTML.
Props is short for properties and they are used to pass data between React components. 
React’s data flow between components is uni-directional.

## how to pass data with props
In React, you can pass props, or properties, to child components.
Say you have an App component which renders a child component called name which is a stateless functional component
You can pass name  a user property by writing:


class ParentComponent extends Component {    
    render() {    
        return (        
            <ChildComponent name="First Child" />    
        );  
    }
}

const ChildComponent = (props) => {    
    return <p>{props.name}</p>; 
};

