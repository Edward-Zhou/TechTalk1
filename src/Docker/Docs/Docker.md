## Create Asp.Net Core Project

`dotnet new mvc -o DockerCoreApp`

## Create dockerfile

`type nul>dockerfile`

## dockerfile content

```

```

## check generated image

`docker image ls`

## run docker container

`docker run -it -p 8080:80 --name dockercoreapp1 dockercoreapp:v1`

## mount 