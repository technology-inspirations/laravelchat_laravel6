# Laravelchat Build in Laravel 6

# ** Getting Started ** 

```
git clone https://github.com/technology-inspirations/laravelchat_laravel6.git
composer install
php artisan key:generate
```

# ** Setup Pusher **

If you don't have one already, create a ** free Pusher account**  at ** https://pusher.com/signup ** then login to your dashboard and create an app.

Set the BROADCAST_DRIVER in your .env file to pusher:

```
BROADCAST_DRIVER=pusher
```

Then fill in your Pusher app credentials in your .env file:

```
PUSHER_APP_ID=xxxxxx
PUSHER_APP_KEY=xxxxxxxxxxxxxxxxxxxx
PUSHER_APP_SECRET=xxxxxxxxxxxxxxxxxxxx
PUSHER_APP_CLUSTER=
```

# ** Database Migrations ** 

Be sure to fill in your database details in your ** .env ** file before running the migrations:

```
php artisan migrate
php artisan serve
```

and visit ** http://localhost:8000/ ** to see the application in action.
