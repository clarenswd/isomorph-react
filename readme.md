#To build the fron end 
`NODE_ENV=production node_modules/.bin/webpack -p`
#To Run Front end webpack server
`node_modules/.bin/http-server src/static`

#To run Server {back end | isomorphic App}
`NODE_ENV=production node_modules/.bin/babel-node --presets 'react,es2015' src/server.js`

Code from the following Tutorial
https://scotch.io/tutorials/react-on-the-server-for-beginners-build-a-universal-react-and-node-app?utm_content=buffer1f683&utm_medium=social&utm_source=facebook.com&utm_campaign=buffer

