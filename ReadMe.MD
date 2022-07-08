
#### Run Build Docker
1. Masuk Direktori My API
```
cd my_api
```
2. Build Image
```
docker build -t my_api .
```
3. Run Container
```
docker run -d --name my_api -p 3000:3000 my_api
```
4. Open Browser and Enter URL
```
http://localhost:3000
```
5. Stop Docker Container
```
docker stop my_api
```
6. Remove Docker Container
```
docker rm my_api
```

#### Docker Compose
1. Masuk direcktori Blog
2. cp .env.example .env
3. edit .env 
4. run docker compose
```
docker compose up -d
```
5. stop docker compose
```
docker compose down
```
6. rebuild docker compose and run
```
docker compose up -d --build
```