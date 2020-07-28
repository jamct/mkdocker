# MkDocker
MkDocs in Docker container. 

## Usage

Clone this repository. Write docs to `container/mkdocs/docs`.


## Develop docs
For development start with docker-compose:

```
docker-compose -f docker-compose-dev.yml up
```

Container starts an page is running on port 8080. You can live edit.


## Run in production

For production start with docker-compose:

```
docker-compose up -d
```

