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

### 1.Template engine
We use BladeOne (Independent template engine but it look like laravel blade)

#### install
```bash
composer require eftec/bladeone
```

### 2. Routing System
