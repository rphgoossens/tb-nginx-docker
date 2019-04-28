# tb-nginx-docker
Project used to build a NGINX image with a predefined configuration used to load balance a spring boot application.
The image is used by the **tb-springboot-docker** project.
## Building the image
To build the image issue the following docker command:
```console
docker build --tag rphgoossens/tb-nginx-docker:tb-docker-2.0 .
```


