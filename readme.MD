# React Js

The client side or commonly called as UI is built using React-Js

### Creating an element using react

```Js
React.createElement(type,prop)
```
type:- div,h1,p1,etc  
prop:- classname,onclick,id,etc  

Example:- 

```js
const root = document.getElementById("root");
const element = React.createElement("h1", { className: "greeting", children: "Hello world" });
ReactDOM.render(element, root); 
```

# Class Component
Building react component using classes. The class is an sub class of component class.  
The render() is used to return JSX elements.

```js
improt {component} from 'react'

class Mycomponent extends component{
    render(){
        return <h1> HELLO WORLD!</h1>
    }
}
```
