# Heroku Static Site Deployment
Heroku hosts apps on the internet, not static websites.  
Deploy static website as a PHP app.

## 1. Create ```composer.json```
```
{}
```

## 2. Create ```index.php```
```
<?php include_once("home.html"); ?>
```

## 3. Rename the homepage (e.g. index.html) to home.html


## 4. Add the Heroku button in ```Readme.md```
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/OttawaSTEM/Heroku-Static/)


## 5. Connect Github to Heroku
### 5.1 Under Heroku application -> "Deploy" -> "Deployment method"
### 5.2 Choose "Github Connect to Github"
### 5.3 Authenticate Github to Heroku
### 5.4 Click "Search" and choose repository from Github -> "Connect"
### 5.5 Click "Enable Automatic Deploys"