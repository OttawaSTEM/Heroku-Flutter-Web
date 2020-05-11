# Heroku Static Site Deployment
Heroku hosts apps on the internet, not static websites.  
Deploy static website as a PHP app.

## 1. Create ```composer.json```
```
{}
```

## 2. Create ```index.php```
Not embed
```
<?php include_once("home.html"); ?>
```
Embed
```
<?php include_once("index.html"); ?>
```

## 3. Rename the homepage (e.g. index.html) to home.html

## 4. Create a 'Deploy to Heroku' Button for Github Deployment
Create ```app.json``` file
```
{
    "name": "Heroku Flutter-Web Github deployment",
    "description": "Heroku Flutter-Web Github deployment",
    "repository": "https://github.com/OttawaSTEM/Heroku-FlutterWeb/",
    "logo": "https://ottawastem.com/static/site/img/logo-big.png",
    "keywords": ["heroku", "php", "github", "Flutter Web"]
}
```

## 5. Add the Heroku button in ```Readme.md``` for Github
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/OttawaSTEM/Heroku-FlutterWeb/)

## 6. Connect Github to Heroku
### 6.1 Under Heroku application -> "Deploy" -> "Deployment method"
### 6.2 Choose "Github Connect to Github"
### 6.3 Authenticate Github to Heroku
### 6.4 Click "Search" and choose repository from Github -> "Connect"
### 6.5 Click "Enable Automatic Deploys"