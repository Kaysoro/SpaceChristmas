# Santarminator
## *For an awesome Christmas Newsletter*

![](http://3.bp.blogspot.com/-kTKYuzbFEns/Urnkbujc7RI/AAAAAAAAVQY/0g93xV4wTGw/s1600/Santa11.jpg)

## Development
> npm install  
> node index.js

# Docker

[![](https://img.shields.io/docker/automated/jrottenberg/ffmpeg.svg?style=for-the-badge)](https://hub.docker.com/r/babilling/santarminator/)

- Build it yourself :
```
docker build -t santarminator .
```

- Run it from Dockerhub :
```
docker run --name santarminator -d -v myvolumedb:/santarminator/db/ -v myvolumelog:/opt/log/ -p YOURPORT:8080 babilling/santarminator
```
