# docker-sonarqube

This is a fork of [mpas/docker-sonarqube](https://github.com/mpas/docker-sonarqube) but using [SonarQube 7.1](https://hub.docker.com/_/sonarqube/). Among other thing, using this version you can bind your SonarLint with the server without any dependendency issues.

This image contains manual installed plugins. The default provided plugins are removed and replaced by manual downloaded.

To add/remove plugins modify the Dockerfile and build your own version.

### Run the image locally

```bash
docker run -d --name sonar -p 9000:9000 --rm cesdperez/docker-sonarqube
```
