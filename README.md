# heroku-buildpack-testssl

[Heroku Buildpack][Buildpacks] to make [`testssl.sh`](https://testssl.sh/) available to your Heroku application.

Usage:

    heroku buildpacks:set https://github.com/dentarg/heroku-buildpack-testssl

    # if you use multiple buildpacks
    heroku buildpacks:add --index 2 https://github.com/dentarg/heroku-buildpack-testssl

See the Heroku documentation for more information:

* [Buildpacks]
* [Using Multiple Buildpacks for an App](https://devcenter.heroku.com/articles/using-multiple-buildpacks-for-an-app)
* [Heroku Buildpack Registry](https://devcenter.heroku.com/articles/buildpack-registry)

[Buildpacks]: https://devcenter.heroku.com/articles/buildpacks
