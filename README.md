# Ionic Framework Image

### Usage

Build
```
docker build -t mojemeno123/docker-ionic .
```

Simply run
```
docker run -it mojemeno123/docker-ionic sh
```

Port fowarding and PersistentVolume
```
mkdir app
docker run -it -p 8100:8100 -v $(pwd)/app:/usr/src/app mojemeno123/docker-ionic sh
```
