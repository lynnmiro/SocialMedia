
# socialmedia
### Install dependencies for server
npm install

### Install dependencies for client
npm run client-install

### Run the client & server with concurrently
npm run dev

### Run the Express server only
npm run server

### Run the React client only
npm run client

###### Server runs on http://localhost:5000 and client on http://localhost:3000

You will need to create a keys.js in the server config folder with


module.exports = {
  mongoURI: 'YOUR_OWN_MONGO_URI',
  secretOrKey: 'YOUR_OWN_SECRET'
};
>>>>>>> a9e0b9b7e2e4a21ab804930dc1afd9ae9cab3712
