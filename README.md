Readme
======
Template for using wordpress + docker + git.

Only your theme and plugin files are in version control. All wordpress
files use the docker container. \o/

Requirements
------------
1. [Docker](https://www.docker.com/) ([Boot2Docker](http://boot2docker.io/) if on OSX)
1. [Docker-Compose](https://docs.docker.com/compose/)


Usage
-----

1. Your plugins go in `/plugins`
1. Your theme goes in `/theme`
1. within this directory run `docker-compose up`
1. navigate to `http://your-docker-ip:3000`

Side Note
---------

The docker compose file specifies a specific wordpress version. You should
adjust this to whatever you are supporting / using in production. The list
of released wordpress versions can be found [here](https://registry.hub.docker.com/_/wordpress/tags/manage/).
