Heroku buildpack for azcopy
================================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks)
that allows one to run azcopy in a dyno alongside application code.

# Testing buildpack locally

```sh
DOCKER_DEFAULT_PLATFORM=linux/amd64 docker build .
```
