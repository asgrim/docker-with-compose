[https://hub.docker.com/repository/docker/asgrim/docker-with-compose](https://hub.docker.com/repository/docker/asgrim/docker-with-compose)

## Tags

 * 19.03.1
 * 19.03.13

# Building & tagging

 * `export TAG_VERSION=19.03.13` (update this)
 * `docker build -t asgrim/docker-with-compose:$TAG_VERSION .`
 * `docker push asgrim/docker-with-compose:$TAG_VERSION`
 * `git tag -s $TAG_VERSION`
 * `git push && git push origin $TAG_VERSION`
