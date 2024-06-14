# json-server
json server for local testing

- npm install json-server <br/>
- Create a db.json or db.json5 file <br/>
- npx json-server grid.json <br/>
- curl http://localhost:3000/posts/1 //sample of using it via command line or browser can be used<br/>
- http://localhost:3000/storage/1   //another sample for parameter usage 
- To read the environment variable from .env file, we require some parser to make it work.<br/>
  There is an npm package called dotenv is a zero-dependency module that loads environment variables from a .env file into process.env object.<br/>
  - npm install dotenv<br/>
  Requiring Module: Require dotenv package in the app using the following code:<br/>
  - require('dotenv').config(); //in index.js file use
  e.g console.log("PORT:", process.env.PORT); 