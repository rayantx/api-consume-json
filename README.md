<h1 align="center">
    <img src="golang_logo.png">
    <p>GO JSON consume API</p>
</h1>

## ⭐ ABOUT

A API JSON consume using **Go, MongoDB, Docker, Postman.**

## 🔨 TOOLS

- [Go](https://go.dev/)
- [Docker](https://www.docker.com/)
- [MongoDB](https://www.mongodb.com/)
- [Postman](https://www.postman.com/)

## ✨ GETTING STARTED

Ensure you have the following installed on your system:

- Docker (with MongoDB)
- Postman

## 🔧 INSTALLATION

1. Clone the repository:
```bash
git clone https://github.com/rayantx/api-consume-json.git
```
2. Install your MongoDB image with Docker:
```bash
docker run --name your_db -p 27017:27017 -d mongo
```

## 🎡 USAGE

**RUN** in terminal with Go
```bash
go run main.go
```

**GET** in **Postman**
```bash
http://localhost:3000/facts
```

Your **RESPONSE**
```bash
{
    {"_id":"66ca2e4ef7eab8d727192d4a","fact":"The cat appears to be the only domestic companion animal not mentioned in the Bible.","length":84},
    {"_id":"66ca2e50f7eab8d727192d4b","fact":"All cats have claws, and all except the cheetah sheath them when at rest.","length":73},
    ...
}
```


