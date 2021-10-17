# Developer Environment

## Build Image with VS Build Tools 2019

`docker build --pull --rm -f "BuildTools2019\DockerFile" --target buildtoolsfinal -t buildtools:2019 "BuildTools2019"`

## Build Image with Wix 3.11

`docker build --pull --rm -f "BuildTools2019\DockerFile" -t wix:311 "BuildTools2019"`
