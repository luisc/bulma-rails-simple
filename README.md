# Basic Bulma Rails 7

Didn't want to use webpacker. From a default:

    rails new app_name

- add to Gemfile: gem "cssbundling-rails"
- $ bundle
- yarn add bulma (install yarn if necessary)
- add node_modules to .gitignore
- rails css:install:sass
- in app/assets/stylesheets/application.sass.scss add: @import 'bulma/bulma';
- rails css:build

Check [cssbundling-rails](https://github.com/rails/cssbundling-rails) for info on continually recompiling assets during development.
