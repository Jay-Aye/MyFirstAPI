# MyFirstAPI

## Node + Express + MongoDB API

Base API that can be built upon
Built with help from https://medium.freecodecamp.com/building-a-simple-node-js-api-in-under-30-minutes-a07ea9e390d2

#### add db.js file to './config'
`$ touch db.js`
```javascript
module.exports = {
  url : "mongodb://USERNAME:PASSWORD@ds131312.mlab.com:31312/myfirstapi"
}
```

Database collection will generate as 'notes' with a 'id', 'title' and 'text' field

MongoDB Deployment on https://mlab.com/ . For Development only.
