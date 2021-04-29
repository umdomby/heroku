# heroku
https://dashboard.heroku.com/apps/

git init

ctr+alt+a  or git add .

git commit -m "first commit"

heroku login

heroku create

heroku config:set MONGODB_URI="mongodb+srv://user:user@cluster0.fv5ou.mongodb.net/myFirstDatabase?retryWrites=true&w=majority"

git push heroku master

heroku open

heroku config:get MONGODB_URI

