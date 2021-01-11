# The Loop
Have you ever gotten a request to add a feature to your project by 'putting it in the "loop"'?
> We need to track user purchases with this code, it's a simple implementation: put it in the "loop".

This repo allows you to find this mysterious "loop" and add whatever you want to it; satisfying both you and your employeer!

# How it works
```javascript
const { loop } = require("npm-loop");

function marketingRequest() {
    // ...
}

loop.push(marketingRequest); // [ [Function: marketingRequest] ]
```

# Install
```
npm install the-loop
```