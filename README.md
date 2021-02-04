# mastering-apis
This is me mastering APIs

What the heck a API

Here is my example how to make a request

```js
// Requests to a third party database that returns a json object
fetch('https://api.github.com/users/facebook') // endpoint
.then(response => {
    return response.json(); // change this reponse so we can work with it in JavaScript
})
.then(data => {
    console.log(data);
});
```