# Changelog

## 0.0.7 (unreleased)

### features

### improvements

- use environment variable to define secret_token and secret_key_base
- complete refactor of Heroku app creation and configuration
- ask for user credentials before creating the Heroku app
- set the correct timezone config on heroku after creating the app

### bug fixes

- don't break if you choose an already taken name for your Heroku app
- remove the `root_url` from application.html.haml since there's no default `root_url`
- remove duplicated gems (foreman and letter_opener) from the default Gemfile

## 0.0.6 (August 16, 2013)

### features

### improvements

### bug fixes

- Fix integration bug

## 0.0.5 (August 16, 2013)

### features

### improvements

- added rails_12factor gem
- added missing turbolinks on layout
- removed valid_attribute gem
- created partials from error messages and flash messages
- added jumpup over integration from github
- use `heroku config:set` and `heroku config:unset`
- added SecureHeaders initializers
- added locale configs as Brazil
- no more ask for ruby version or gemset name
- add required ruby 2.0.0 or greater

### bug fixes

- added --app param to heroku lock and unlock tasks
- resolved bug with rvm current when the bin is not properly set
- fix already initialized constant APP on `tasks.rake` and `integration.rake`

## 0.0.4 (July 19, 2013)

### features

### improvements

- Use the new rspec expect syntax
- Halt if Heroku app already exists.
- Do not say "Pushing application to Heroku" if there is no deploy
- Do not install Sendgrid unless user explicitely says so
- Using user input for Heroku app name
- Changed readme
- Heroku tasks now run out of Bundler environment
- Cleaning old stuffs
- Show suggestion of heroku app
- Export APP on .rvmrc
- Updated to Rails 4.0 and Ruby 2.0

### bug fixes

## 0.0.3 (July 05, 2013)

### features

### improvements

- Added badges
- Updated rvm
- Added bourbon
- Removed the include of requires.rb
- Removed unused gems (like Timecop) from the default Gemfile
- Added Unicorn awesome configuration
- Making clear that we use ruby 1.9.3
- Added integration

### bug fixes

## 0.0.2 (June 20, 2013)

### features

### improvements

- Removed a lot of old stuffs
- Changed Flag on Cli to Pah
- Removed old comments
- Updated all gems
- Removed a missing README

### bug fixes

- Fixed bug on add letter\_opener

## 0.0.1 (June 17, 2013)

### features

- Changed rails-template to a gem named pah

### improvements

- Better readme

### bug fixes

## Previous

The changelog began with version 0.0.1 so any changes prior to that
can be seen by reading old git commit messages.
