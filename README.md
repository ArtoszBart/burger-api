# burger-api
Burger API to learn simple APIs.

[API site](https://art-burger-api.herokuapp.com/)

## To get burger by ID

```
fetch('https://art-burger-api.herokuapp.com/burgers/[BURGER_ID]')
  .then(response => response.json())
  .then(data => console.log(data));
```
