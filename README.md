# lern-goharbor
lerning goharbor

## login

```
docker login demo.goharbor.io
```

## Create a very simple Dockerfile with the following contents.

```
FROM busybox:latest
```

## Build an image from this Dockerfile and tag it

```
docker build -t demo.goharbor.io/your-project/test-image .
```

## Push the image to your project in Harbor

```
docker push demo.goharbor.io/your-project/test-image
```

Harbor interface, go to `Projects` > `your_project` > `Repositories` to view the image repository that you pushed to your Harbor project








