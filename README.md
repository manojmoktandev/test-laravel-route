## Test Laravel Routing
This repository is a simply test driven for  `routes/web.php` and `routes/api.php`

In both of those files, You  will find comments, describing 12 tasks. For majority of the tasks, you need to write ONE line of code.

Example:

```
// Task 2: point the GET URL "/user/[name]" to the UserController method "show"
// It doesn't use Route Model Binding, it expects $name as a parameter
// Put one code line here below
```

To test if all the routes work correctly, there are PHPUnit tests in `tests/Feature/RoutesTest.php` file.

In the very beginning, if you run `php artisan test`, or `vendor/bin/phpunit`, all 8 tests fail.
Your task is to make those tests pass.



