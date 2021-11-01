# Dev Container

![Build Dev Container](https://github.com/ateamsw/devcontainer/workflows/Build%20Dev%20Container/badge.svg)

A project for creating a dev container that can be used with VS Code's remote development functionality.

## Build Locally

```bash

docker build -t moderndevinaction/devcontainer:latest .

docker push moderndevinaction/devcontainer:latest

docker run -it --rm moderndevinaction/devcontainer:latest

```

## GitHub Actions

This project uses GitHub Actions and the [`publish-container-image.yaml`](.github/workflows/publish-container-image.yml) file to build and push
this image to the [GitHub Container Registry](https://ghcr.io/moderndevinaction/devcontainer:latest).

## Follow Up

Email chwieder@microsoft.com for more information on this container and scenarios for usage.
