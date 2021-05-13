# MyTshirt

This is the backend of MyTshirt E-commerce website project.
[Link to Working project's website](https://myshirtstore.herokuapp.com/)

### Tech Used

- [MongoosJS]
- [node.js]
- [Express]
- [Stripe]

### How to clone and run this project to your system.

```sh
$ git clone https://github.com/NaveenMohanty/mytshirt-backend.git
$ cd mytshirt-backend
$ npm install
$ node app.js
```

### This project has .env file for Environment Variable.

```
DATABASE = '<--Mongo DB URL Here--->'
PORT = 9000
SECRET = Tshirts // any hash key for password encryption
STRIPE_SK ="<--Secret key of your stripe payment gateway-->"
```

> This project use stripe as payment gate so u have to use it's Secret key which is present in your [stripe] dashboard.
> Make a .env file to declare all the above environment variabale.

[mongoosjs]: https://mongoosejs.com/
[node.js]: http://nodejs.org
[express]: http://expressjs.com
[stripe]: https://www.npmjs.com/package/stripe
