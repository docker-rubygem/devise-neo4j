[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/devise-neo4j.svg)](https://hub.docker.com/r/rubygem/devise-neo4j/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/devise-neo4j.svg)](https://hub.docker.com/r/rubygem/devise-neo4j/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/devise-neo4j.svg)](https://hub.docker.com/r/rubygem/devise-neo4j/)
[![Gem Downloads](https://img.shields.io/gem/dt/devise-neo4j.svg)](https://rubygems.org/gems/devise-neo4j/)
# devise-neo4j

Auto-Generated Docker image for devise-neo4j to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/devise-neo4j`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/devise-neo4j`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/devise-neo4j`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/devise-neo4j/)
