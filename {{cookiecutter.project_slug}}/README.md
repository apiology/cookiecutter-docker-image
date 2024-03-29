# {{ cookiecutter.project_name }}

[![CircleCI](https://circleci.com/gh/apiology/{{cookiecutter.project_slug}}.svg?style=svg)](https://circleci.com/gh/apiology/{{cookiecutter.project_slug}})

WARNING: This is not ready for use yet!

{{ cookiecutter.project_short_description }}

```sh
docker pull {{ cookiecutter.full_docker_image_name }}:latest
```

To build locally, run `make`.  You can see images at
[Docker Hub](https://hub.docker.com/repository/docker/{{ cookiecutter.full_docker_image_name }})

## Contributions

This project, as with all others, rests on the shoulders of a broad
ecosystem supported by many volunteers doing thankless work, along
with specific contributors.

In particular I'd like to call out:

* [Audrey Roy Greenfeld](https://github.com/audreyfeldroy) for the
  cookiecutter tool and associated examples, which keep my many
  projects building with shared boilerplate with a minimum of fuss.
