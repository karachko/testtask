# testtask
- I took the ready froject from github (https://github.com/urakaiketsuya/docker-laravel-vue)
- I changed for laravel(laravel folder)  ports:  - "9000:9000" in file https://github.com/karachko/testtask/blob/main/laravel/docker-compose.yml
- I changed file (laravel/nginx )https://github.com/karachko/testtask/blob/main/laravel/nginx/default.conf
 - I addes to the /etc/hosts (127.0.0.1 api.app.local and 127.0.0.1 app.local)
 - Into the laravel folder I executed docker-compose up
 - but redirection to api.app.local and app.local is not working. I do not know. I all did well
 
