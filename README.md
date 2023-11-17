# Laravel Quick Start

This is a basic guide to get you started with a Laravel project using the Laravel installer.

## Step 1: Install Laravel

Make sure you have [Composer](https://getcomposer.org/) installed.


laravel new hello_world

<button data-clipboard-text="composer create-project --prefer-dist laravel/laravel your-project-name
cd your-project-name">Copy</button>

Replace your-project-name with your desired project name.

Step 2: Create a Controller
Generate a controller named HomeController using Artisan.

php artisan make:controller HomeController

<button data-clipboard-text="php artisan make:controller HomeController">Copy</button>

Edit the HomeController.php file in app/Http/Controllers:

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

Step 3: Define a Route
Open the routes/web.php file and add a route for the HomeController:

// routes/web.php

use App\Http\Controllers\HomeController;

Route::get('/', [HomeController::class, 'index']);

<button data-clipboard-text="// routes/web.php

use App\Http\Controllers\HomeController;

Route::get('/', [HomeController::class, 'index']);">Copy</button>

Step 4: Run the Laravel Development Server

php artisan serve

<button data-clipboard-text="php artisan serve">Copy</button>

Visit http://localhost:8000 in your web browser to see the "Hello, Laravel!" message.

This is a basic setup, and you can now explore more features and build on top of Laravel for your project.

Now, this guide starts from creating a new Laravel project using Composer. If you have any further questions or adjustments you'd like, feel free to ask!

