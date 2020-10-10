# laravel_8_auth
This is a simple laravel 8 app that teaches how to do user registration and login.
The repository is the code to one of my article on **Dev.to**, [Laravel 8 Auth (Registration and Login)](https://dev.to/kingsconsult/laravel-8-auth-registration-and-login-32jl) the article will teach you how to do user authentication in Laravel 8, the method is applicable to Laravel 6 and also Laravel 7 

## How to install and run on your local system
1. git clone https://github.com/Kingsconsult/laravel_8_auth.git
2. cd laravel_8_auth/
3. composer install
4. npm install
5. cp .env.example .env
6. php artisan key:generate
7. Add your database config in the .env file (you can check my articles on how to achieve that)
8. Add your email address and the password in the .env
![.env file](https://res.cloudinary.com/kingsconsult/image/upload/v1600318472/15_ed1xxx.png)
9. php artisan migrate
10. php artisan serve (if the server opens up, http://127.0.0.1:8000,  then we are good to go)
![localhost](https://res.cloudinary.com/kingsconsult/image/upload/v1600705305/laravel%208%20modal/4_pp7r76.png)

Holding down the Ctrl button and Clicking the localhost http://127.0.0.1:8000/ will serve our app in our default browser
![homepage](https://res.cloudinary.com/kingsconsult/image/upload/v1602275187/laravel%208%20gmail/4_fiftn6.png)

Then click on register by the top-right to register an account,
![register page](https://res.cloudinary.com/kingsconsult/image/upload/v1600318471/10_rqgzrc.png)

will give us this page, filling your name, email address and password and submitting will take us to the our dashboard
![Dashboard](https://res.cloudinary.com/kingsconsult/image/upload/v1600318472/11_htzvj5.png)

## Operations
1. Register to the app
2. Visit the dashboard
3. Log out
4. Log in
5. Reguest to reset password
6. Reset password
7. Edit profile
8. Enable two-factor Authentication
