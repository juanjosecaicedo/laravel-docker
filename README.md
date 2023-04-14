# laravel-docker

A brief description of what this project does and who it's for

#Custom CLI Commands
- `bin/cli`: Run any CLI command without going into the bash prompt. Ex. `bin/cli ls`
- `bin/install` create new project in `src` folder
- `bin/start` start project
- `bin/stop` stop project
- `bin/status` Check the container status.
- `bin/restart` Stop and then start all containers.
- `bin/artisan`: Run the Artisan CLI. Ex: `bin/artisan list` or `bin/laravel list`
- `bin/composer`: Run the composer binary. Ex. `bin/composer install`
- `bin/npm`: Run the npm binary. Ex. `bin/npm install`
- `bin/stopall`: Stop all docker running containers