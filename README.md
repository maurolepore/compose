This repo is a platform to launch Docker containers reusing R libraries
via a volume managed by Docker.

Launch the service with:

```bash
docker-compose run service
```

Launch R, then reuse the library with:

```r
.libPaths('/rlib')
```
