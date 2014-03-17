express-mongoose-docs
=====================

This module will take away the pain of writing API and Data Model documentation for your Express & Mongoose based API


Installation
--------------

* Step 1

```sh
npm install express-mongoose-docs
```

* Step 2

Add these lines to your app.js file

```sh
var docs = require("express-mongoose-docs");
```

```sh
docs(app, mongoose); // If you don't use mongoose you can skip the 2nd param
```

* Step 3

The Docs web page can be accessed at Your-Base-URL/apiDocs

Example: http://localhost:5000/apiDocs

Screenshots
===========

![routes](https://raw.github.com/nabeel-ahmad/express-mongoose-docs/master/screenshots/screenshot1.png "Routes")

![data-model](https://raw.github.com/nabeel-ahmad/express-mongoose-docs/master/screenshots/screenshot2.png "Data Model")



[repository]:https://github.com/nabeel-ahmad/express-mongoose-docs

