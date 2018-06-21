## Build
> docker build -t android-sdk -f scripts/PackSdkDockerfile .

### Purge
> docker system prune

## Enter docker image
> docker run -i -t --entrypoint /bin/bash
