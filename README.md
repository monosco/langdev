# LangDev is a Dockerfile (with Kakao)

## List of languages
 - Swift 4.1.1
 - Java 1.8.0
 - Python 3.6.5

## Build
```sh
docker build -t monos/langdev .
```

## Create a Container from the Image and Attach It
```sh
docker run --privileged --name langdev -ith langdev monos/langdev
```
