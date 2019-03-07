# docker
Docker Hub can automatically build images from source code in my github repository included multiple Dockerfiles and automatically push the built image to my Docker repositories.

### Set Dockerfile location
- Docker Hub can specify the **Dockerfile location** as a path relative to the build context.
- If the Dockerfile is at the root of ther build context path, leave the Dockerfile path set to `/`.
(If the build context field is blank, set the path to the Dockerfile from the root of the source repository.)
