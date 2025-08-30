# Mvc Structure
This repository is a structure of a project with MVC architecture (without frameworks like Laravel and Symfony).

## Project Structure
```txt
Mvc-Without-Laravel/
│
├── composer.json
├── composer.lock
├── index.php
├── .htaccess
│
├── views/
│   └── main.blade.php
│
├── controllers/
│   └── controller.php
│
├── models/
│
├── vendor/
│
└── cache/
```

## Requirements
1. Template Engine
2. Routing System
3. Apache Configuration

### 1.Template engine
We use BladeOne (Independent template engine but it look like laravel blade)

https://github.com/EFTEC/RouteOne
#### Installation
```bash
composer require eftec/bladeone
```

### 2. Routing System
https://github.com/bramus/router

#### Installation
```bash
composer require bramus/router ~1.6
```

### 3. Apache Configuration
Create .htacces file and write this code in the file.
```perl
RewriteEngine On
RewriteCond %{REQUEST_FILENAME} !-f
RewriteCond %{REQUEST_FILENAME} !-d
RewriteRule ^ index.php [QSA,L]
```
### :)
