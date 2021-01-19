# Create simple http server and deploy it to heroku
## Initial setup
* `mkdir node-heroku-server`
* `npm init -y`
* add "start":"node server.js" to package.json
* add server.js file
* `git init`
* add .gitignore file

Run `npm run start` and check that it works locally with postman

## deploy to heroku
[link docs](https://www.heroku.com/nodejs).

* `heroku create`
* `git push heroku master`

Run [heroku link](https://node-heroku-server.herokuapp.com/) and check that it works on heroku with postman

## Rename heroku app name
[usefull doc](https://devcenter.heroku.com/articles/renaming-apps)
* `git remote rm heroku`
* `heroku git:remote -a node-heroku-server`
* `git push heroku`
