# Rails Vue
Sample rails project integrates with webpacker and vue.

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
bundle exec rake assets:precompile
bundle exec rake webpacker:compile
SECRET_KEY_BASE=secret RAILS_SERVE_STATIC_FILES=1 rails server -e production
```

## Environment
 - Ruby 2.5.0
 - Rails 4.2.11.1
 - Node 10.15.0
 - Yarn 1.12.3
