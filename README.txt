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



=== SERVER
---------------------------------------
git init
git add .
git commit -m "First commit"
heroku create navatar-mern

or

heroku git:clone -a navatar-backend
git commit -m "First commit"
---------------------------------------
git push heroku master

const PORT = process.env.PORT || 5000

=== POSTGRES
module.exports = new Sequelize(process.env.DATABASE_URL, {
    dialect: 'postgres',
    protocol: 'postgres',
    dialectOptions: {
        ssl: {
            require: true,
            rejectUnauthorized: false
        }
    }
});


