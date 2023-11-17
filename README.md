# Laravel Quick Start

This is a basic guide to get you started with a new Laravel project.

## Step 1: Create a Project in Laravel

<details>
  <summary>Step 1 Command : </summary>
  laravel new hello_world
</details>

## Step 2: Goto that directory 

<details>
  <summary>Step 2 Command : </summary>
  cd hello_world
</details>

## Step 3: Create a Controller 

Generate a controller named HomeController using Artisan.

<details>
  <summary>Step 3 Command : </summary>
  php artisan make:controller HomeController
</details>

Edit the HomeController.php file in app/Http/Controllers:

<details>
  <summary>Step 3 Command : </summary>
  // app/Http/Controllers/HomeController.php

namespace App\Http\Controllers;

use Illuminate\Http\Request;

class HomeController extends Controller
{
    public function index()
    {
        return "Hello, Laravel!";
    }
}

</details>
