# ✨ Heroku buildpack for asset precompile

The following is not running as part of the heroku deploy for motorefi-dev and motorefi-demo
```
remote: -----> Preparing app for Rails asset pipeline
remote:        Running: rake assets:precompile
remote:        Webpacker is installed 🎉 🍰
remote:        Using /tmp/build_c3ab0bc3/config/webpacker.yml file for setting up webpack paths
remote:        Compiling…
remote:        Compiled all packs in /tmp/build_c3ab0bc3/public/packs
remote:        Asset precompilation completed (56.28s)
remote:        Cleaning assets
remote:        Running: rake assets:clean
```

This buildpack should run `rake assets:precompile`
