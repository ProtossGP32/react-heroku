# Deploy React App With Heroku

## Live link to Heroku
[Heroku](https://m3-react-heroku.herokuapp.com/)

## Available Scripts

In the project directory, you can run:

### `npm install`

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

### `npm run build`


# Short steps was made to deploy:

-1. ### `npx create-react-app react-heroku`

-2. create new empty repo <react-heroku>

and [add buildpack in heroku](https://github.com/mars/create-react-app-buildpack)

-3. run commands in terminal:
### `$ heroku login`

### `$ heroku git:remote -a m3-react-heroku`

here name which created in heroku - "m3-react-heroku"

### `$ git remote -v`

### `$ git push heroku react-heroku`

-4. 
### `$ git add .`

### `$ git commit -am "make it better"`

$ git push heroku main

WAIT FOR A MOMENT WHILE A SCRIPT FINIHES

YOU SHOULD SEE A LINK TO PROJECT

-5. when I updated my project, I run this command again to get update heroku link:

### `$ git push heroku main`
