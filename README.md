# isce2-docker
build [isce2](https://github.com/isce-framework/isce2) docker image with github actions

![Action Status](https://github.com/scottyhq/isce2-docker/workflows/publish-docker/badge.svg)

* commits to master branch trigger re-building 'latest' image 
* pushing a tag results in a docker image with the same tag:
```
git tag -am "test v2.3.2" v2.3.2
git push --tags
```

images stored on dockerhub public repo:
https://hub.docker.com/repository/docker/scottyhq/github-action


