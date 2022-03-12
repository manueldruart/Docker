# Docker Compose v2

Docker Compose is a tool for running multi-container applications on Docker
defined using the [Compose file format](https://compose-spec.io).
A Compose file is used to define how the one or more containers that make up
your application are configured.
Once you have a Compose file, you can create and start your application with a
single command: `docker compose up`.

# Where to get Docker Compose

### Windows and macOS

Docker Compose is included in
[Docker Desktop](https://www.docker.com/products/docker-desktop)
for Windows and macOS.

### Linux

You can download Docker Compose binaries from the
[release page](https://github.com/docker/compose/releases) on this repository.

Rename the relevant binary for your OS to `docker-compose` and copy it to `$HOME/.docker/cli-plugins`

Or copy it into one of these folders for installing it system-wide:

- `/usr/local/lib/docker/cli-plugins` OR `/usr/local/libexec/docker/cli-plugins`
- `/usr/lib/docker/cli-plugins` OR `/usr/libexec/docker/cli-plugins`

(might require to make the downloaded file executable with `chmod +x`)
