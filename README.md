# Simple Rest API

A simple REST API created with Go and MongoDB

## Installation

```sh
git clone git@github.com:maumercado/simple-go-crud.git
cd simple-go-crud
```

## Running it

Once you have completed the previous [step](#installation)

```sh
go get
go run main.go
```

## Try it

```sh
curl -X POST -H "Content-Type: application/json" -d '{"Name":"James Bond","Gender":"male","Age":32,"Id":"777"}' http://localhost:8080/user
curl -X GET http://localhost:8080/user/777
```
