# WordPress Installer on your desktop.

WordPress development environment with PHP built-in web server + WP-CLI.

## Requires

* OSX
* php 5.4 or later
* MySQL

## Usage

```
$ mkdir ~/Desktop/wordpress && cd $_
$ curl https://raw.githubusercontent.com/miya0001/try-wp-api/master/run.sh | bash -s <mysql-root-password>
```

### For MAMP users

```
$ mkdir ~/Desktop/wordpress && cd $_
$ curl https://raw.githubusercontent.com/miya0001/wp-instant-setup/master/run.sh | bash -s root
```


### Defaults

* mysql-root-password: (empty)

## Default Account

* User: `admin`
* Password: `admin`
