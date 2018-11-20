# CloudTune

## Installation

To build the cloudtune images from the Dockerfiles, run the commands:

```docker build -t icecast:latest ./docker-icecast/```

```docker build -t ices:latest ./docker-ices/```

The generated docker images can be run with the commands:

```docker run -d -p 8000:8000 icecast:latest```

```docker run -d -p 8001:8001 ices:latest```

**NOTES**

- Early development limitations
  - OGG files must be placed in docker-ices/data/ folder

**TODO**

- Create PVC for OGG files
