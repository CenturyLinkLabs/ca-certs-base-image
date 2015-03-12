# ca-certs

`FROM centurylink/ca-certs`

This is a Docker base image which builds off of the [scratch](https://registry.hub.docker.com/u/library/scratch/) image and adds the root certificates for all of the standard certificate authorities. 

This image is useful for building small images that still require certificate verification for out-bound SSL connections. See the [golang-builder](https://registry.hub.docker.com/u/centurylink/golang-builder/) for more information about creating minimal Docker images with statically-linked Go binaries.
