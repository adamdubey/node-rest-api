# node-rest-api

A RESTful Node.js API featuring Authentication, Protected Routes, and more!

## Usage

1. Create a `nodemon.json` file in the root of the `/server` directory as follows:

```json
{
    "env:" {
        "MONGO_ATLAS_PW": "",
        "JWT_KEY": ""
    }
}
```

Where `MONGO_ATLAS_PW` is the password of your MongoDB Cluster, and `JWT_KEY` can be whatever password you'd like to configure.

2. Start the server locally using either command:

```sh
# normal/standard operation
npm run start

# better logging capabilities
npm run dev
```

## Technologies & Frameworks

- [Node.js]()
- [Express]()
- [Morgan]()
- [MongoDB]()
- [Mongoose]()
- [Multer]()
- [JWT]()
