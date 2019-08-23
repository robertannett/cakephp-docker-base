# Docker base for CakePHP 3.7+

## Installing

* docker-compose build
* docker-compose up

## Example usage

### Database Details
'host' => env('MYSQL_URL', null),
'database' => 'cakephp',
'username' => env('MYSQL_USERNAME', 'root'),
'password' => env('MYSQL_PASSWORD', '')

### List all containers
```
docker ps
```

### Execute a command in a container
```
docker exec <container-id> composer update 
```

## Inspiration

Inspiration, code snippets, etc.
* [Cloud 66](https://blog.cloud66.com/deploying-your-cakephp-applications-with-cloud-66/)