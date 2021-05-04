#Symfony project template

This is a repo to start with good vibes a web project with integration of Webpack Encore and Bootstrap.

## Starting

Run the following commands :

````
composer install
yarn install
yarn encore dev
symfony serve -d
````

Create a .env.local file at the root, use as model the .env file

###Primary files

Scss : /assets/styles/app.scss <br>
JS : /assets/app.js <br>
Images : /assets/

Run ``` yarn encore dev``` to compile assets, automatically done in /public/build/ if success
