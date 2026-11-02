# choose-your-sport

An empty Ruby on Rails 6 application skeleton, generated with `rails new` for an app idea called "Choose Your Sport". No features were built.

## Context

Learning project. The repository has a single commit ("rails new", 8 January 2021) and contains only the files Rails generates for a new app. There are no models, controllers, views, routes, migrations or tests beyond the defaults, and the app never got past the scaffolding step.

## Stack

- Ruby 2.6.6, Rails 6.0 (`~> 6.0.3`)
- SQLite 3, Puma
- Webpacker 4, Turbolinks, Sass
- Minitest with Capybara and Selenium for system tests (no tests written)

## Running it

With Ruby 2.6.6, Bundler, Node.js and Yarn installed:

```bash
bundle install
yarn install
bin/rails db:prepare
bin/rails server
```

The app shows only the default Rails welcome page, because no routes are defined.

## Status

Archived learning project, not maintained.
