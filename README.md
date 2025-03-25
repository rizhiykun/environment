# environment

Little RESTapp for simple sentiment analysis of "Rick and Morty" review

## Getting started

Download repository

```
git clone https://github.com/rizhiykun/environment.git
```

## Init project

Make sure that you already install "make"
```
cd environment
make init_folder
git clone https://github.com/rizhiykun/rickandmorty.git
```

## Configure Hosts
Just add this - 
```
127.0.0.1   traefik.local
127.0.0.1   postgres.local
127.0.0.1   portainer.local
127.0.0.1   redis.local
127.0.0.1   symfony.local
```

## Run project

```
make up
cd rickandmorty
make build
```


## Tests

```
make psalm
make run_unit_test
```

## Swagger

```
http://symfony.local/api/doc
```

