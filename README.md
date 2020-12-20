# What is this?

PHP-TEMPLATE is a template git repository which serves as starting point to your PHP application.
This project requires php and composer to be installed on your system.

# Instalation

#### Clone this repo. From your terminal go to your working folder and run:

```
git clone https://github.com/srivadero/php-template.git
```

#### Install dependencies. From your working folder run:

```
composer uodate
```

#### Write your code and deploy

# Deploy on Heroku
First setup your git repo on  running these commands:

```
git init
heroku login
heroku create your-appname
```

Then deploy your app on each release running the following commands:

```
git add .
git commit -m "your release message"
git push heroku main
```
