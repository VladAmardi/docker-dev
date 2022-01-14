# Usage

```
docker run \
    -v /var/run/docker.sock:/var/run/docker.sock \
    -v /Users/user/Project:/Users/user/Project \
    -ti amardi/docker-dev
```

## Important
Mount point (path) to sources should be equal target point (path)

## Inside
- Based on debian
- Contain: docker, make, curl

## Windows

```
docker run \
    -v /var/run/docker.sock:/var/run/docker.sock \
    -v /С/Users/user/Project:/С/Users/user/Project \
    -ti amardi/docker-dev
```


