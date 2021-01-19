# Create simple http server and deploy it to heroku
## Initial setup
*`mkdir node-heroku-server`
*`npm init -y`
*add "start":"node server.js" to package.json
*add server.js file
*`git init`
*add .gitignore file

Run `npm run start` and check that it works locally with postman

## deploy to heroku
https://www.heroku.com/nodejs
*`heroku create`
*`git push heroku master`
