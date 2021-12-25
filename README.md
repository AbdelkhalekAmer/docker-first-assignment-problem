# Learn how to write docker file, create images and deploy containers

## node-app

build image:

```powershell
docker build -t nodeapp:latest .
```

run container:

```powershell
docker run -p 3000:3000 -d --name nodeapp_latest nodeapp:latest
```

## python-app

build image:

```powershell
docker build -t pythonapp:latest .
```

run container:

```powershell
docker run -it --name pythonapp_latest pythonapp:latest
```

## Listing

- All images

```powershell
docker image ls
```

- All containers

```powershell
docker ps -a
```
