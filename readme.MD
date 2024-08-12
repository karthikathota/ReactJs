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