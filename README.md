# Module 10A - User Authentication

## Short-Answer Questions

1. 
Authentication is verifying who a user is (like logging in with a username and password). Authorization is determining what an authenticated user is allowed to do or access (like checking permissions).

2. 
   Passwords are hashed so that even if the database is exposed or stolen, the actual passwords cannot be read or reversed.

3. 
   Laravel Fortify registers these authentication routes under the hood. You can view registered routes by running `php artisan route:list`.

4. 
   The `auth` middleware acts as a guard that checks if a user is currently logged in. If a logged-out user tries to access a protected page, the middleware blocks them and redirects them to the login page.