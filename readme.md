# Laravel FAQ #

* I've created a workbench package and added the provider in app.php file. When I share it to my peers via source control, they don't seem to get it working on their machine. Composer / artisan doesn't work
	Update the 'autoload' section of the main composer.json file and include the workbench package path in it.