# Installation

* [Fork](https://github.com/sharu725/online-cv/fork) the repository
* Delete the `gh-pages` branch
* Re-create the `gh-pages` branch
* Go to settings and set Github Pages source as master.
* Your new site should be ready at `https://username.github.io/online-cv/`

Change all the details from one place: ``_data/data.yml``

# To preview/edit locally with docker

```sh
docker-compose up
```

*docker-compose.yml* file is used to create a container that is reachable under http://localhost:4000.
Changes *_data/data.yml* will be visible after a while.
