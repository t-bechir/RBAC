dotenv : This package loads environmental variables from a .env  file into Node’s process.env object.
bcrypt : is used to hash user passwords or other sensitive information we don’t want to plainly store in our database.
body-parser : is used to parse incoming data from request bodies such as form data and attaches the parsed value to an object which can then be accessed by an express middleware.
jsonwebtoken : provides a means of representing claims to be transferred between two parties ensuring that the information transferred has not been tampered with by an unauthorized third party, we’ll see exactly how this works later on.
mongoose : is an ODM library for MongoDB, provides features such as schema validation, managing relationships between data, etc…
express : makes it easy to build API’s and server-side applications with Node, providing useful features such as routing, middlewares, etc..
accesscontrol : provides role and attribute-based access control.