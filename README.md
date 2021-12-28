# burger-api
Burger API to learn simple APIs.

[API site](https://art-burger-api.herokuapp.com/)

## Run API
`npm run start`

## HTTP usage
### Show all burgers
/burgers


### Show burger by ID
/burgers/{ID}


## Implementation
### To get burger by ID

```
fetch('https://art-burger-api.herokuapp.com/burgers/[BURGER_ID]')
  .then(response => response.json())
  .then(data => console.log(data));
```

Created to practise APIs, thanks to @github/kubowania tutorial
