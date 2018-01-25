
# How to make this starterpack works?
1.Download and unzip in your local server folder. If you are using xammp path is C:\xampp\htdocs

2.Open your favorite terminal shell( GitBash,CMD...) and go to folder Laravel-TWBS4, using command lines

3. Install node_modules
 
 Type npm install

4. Install vendor  

type composer install

5.Rename .env.example with .env

6.Get and set your App_Key 

type php artisan key:generate and copy that key in .env file and save it
 
Key should look like this base64:aAEcGwzWCcOVBMZuurNNniIxQs9CtosG6fC0vU=

More info: <a href="https://laravel.com/docs/5.5/installation#configuration">Application Key</a>

7.Run your local server. Open your browser and type http://localhost/Laravel5-TWBS4-master/public/, 
if everything went well you should see front page

8.Enjoy





## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
