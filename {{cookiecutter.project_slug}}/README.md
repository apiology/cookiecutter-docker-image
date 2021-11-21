# {{ cookiecutter.project_name }}

[![CircleCI](https://circleci.com/gh/apiology/{{cookiecutter.project_slug}}.svg?style=svg)](https://circleci.com/gh/apiology/{{cookiecutter.project_slug}})

WARNING: This is not ready for use yet!

{{ cookiecutter.project_short_description }}

```sh
docker pull {{ cookiecutter.full_docker_image_name }}:latest
```

To build locally, run `make`.  You can see images at
[Docker Hub](https://hub.docker.com/repository/docker/{{ cookiecutter.full_docker_image_name }})
