# Docker build
```
git clone https://github.com/onespace10/dockerTest
cd dockerTest/UbuntuDocker
docker build --rm -t daya123/ut:v2 .
docker images
```

# Docker run 
```
docker run -it --name ut -v ~/df:/df --rm onespace10/ut:2
```
