# Rails Vue
Sample rails project with webpacker and vue.

## Development
```shell

# Install ruby gems
bundle
# Install node modules
yarn

# Launch webpack-dev-server
./bin/webpack-dev-server

# Run ROR
rails server
```

# Production
```shell
bundle exec rake webpacker:compile
SECRET_KEY_BASE=secret RAILS_SERVE_STATIC_FILES=1 rails server -e production
```
