# MSP430-GCC Docker Image

## Forked

- Forked from: `https://github.com/cdelledonne/docker-msp430-gcc.git`
- Patched with updated URLs and versions.
- Not all functionality of this image has been tested since updating.

Ubuntu-based Docker image equipped with MSP430-GCC, CMake, Doxygen and Sphinx.
Use it in your CI environment to test builds for MSP430 devices and build and
deploy Doxygen/Sphinx documentation.

## Build locally

You can use the provided Dockerfile (and make local modifications to it) to
build an image locally as well:

```sh
git clone https://github.com/nickhrsims/docker-msp430-gcc.git
cd docker-msp430-gcc
docker build --no-cache --pull -t nickhrsims/msp430-gcc:latest .
```
