# Heroku buildpack: deploy script

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) that
allows one to run a script during deploy. This helps support:

1. Compiling dependecies into static slug
2. Running tests on code before it deploys
3. Pulling in system dependencies

## Usage

To use this buildpack we recommend looking into using heroku buildpack mulit

Then add this line to your `.buildpacks` file:

`https://github.com/Litterfeldt/heroku-buildpack-deploy-script`

From here you will need to create a `config/heroku_deploy.sh` file which contains the shell scripts you want to run.

## License

MIT
