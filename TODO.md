
## todo

```
cd myApp
php artisan serve

```

## done

create ```index.php``` if not present then open shell, put
 
```shell

php -S localhost:8001

```

port available on ```8001``` as gitpod url, it

looks like ```https://8001-bronze-pike-1lbuk9fz.ws-us03.gitpod.io/```

```ctrl+c``` to exit.

```shell

php -v
whereis nginx
whereis apache2
whereis composer
service --help
service --status-all
service nginx stop # failed
sudo service nginx stop
whereis mysql
sudo apt-get update
sudo apt-get upgrade
uname -a
#--- config
composer create-project --prefer-dist laravel/laravel myApp
cd myApp
php artisan serve
#added ! to unignore in .gitignmore '/vendor'
sudo apt-get install mysql-server

```

## googled

- https://www.google.com/search?q=how+to+stop+nginx
- https://www.google.com/search?q=how+to+install+laravel+in+ubuntu

## found

- https://notes.etin.space/posts/gitpodifying-a-new-laravel-application
- https://www.hostinger.co.id/tutorial/install-laravel-di-ubuntu
- https://www.howtoforge.com/tutorial/install-laravel-on-ubuntu-for-apache/

## tried

- https://www.hostinger.co.id/tutorial/install-laravel-di-ubuntu#5-Install-Laravel-Ubuntu-dengan-Composer

## fix config

```
git push --force # pass but already fixed using app permition to read or something
composer self-update --2 # failed
add ! to unignore in .gitignmore '/vendor'

```