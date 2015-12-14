source "https://rubygems.org"

gem "rails", "4.1.8"

# Front-end/HTML
gem "uglifier", ">= 1.3.0"
# gem "slim-rails"
# gem "haml-rails", "~> 0.9"
# gem "title"
# gem "simple_form"

# CSS
gem "sass-rails", "~> 5.0"
gem "autoprefixer-rails"
# Uncommend what you need
# gem "bootstrap-sass", "~> 3.3.6"
# gem "foundation-rails" # Foundation 5
# gem "bourbon", "~> 4.2.0"
# gem "neat", "~> 1.7.0"
# Because some frameworks already provides normalization
# gem "normalize-rails", "~> 3.0.0" 

# Javascript
gem "jquery-rails"
# gem "coffee-rails", "~> 4.0.0" # for coffeescript lover
# gem "turbolinks" # i"ll let you decided here
# gem "rack-canonical-host"

# Json
gem "jbuilder", "~> 2.0"

# Authentication/Authorization
# gem "devise"
# gem "omniauth"
# gem "omniauth-facebook"
# gem "omniauth-twitter"
# gem "omniauth-google-oauth2"

# MISC
gem "responders"
# gem "capistrano-rails", :development # use capistrano for quicker deployment 
# gem "airbrake", #airbrake 

# DB
# gem "pg"
# gem "sqlite3"

# Server
# gem "thin", :development # my preference for development
gem "puma" # Use puma as the app server
# gem "unicorn" # Use unicorn as the app server

# Doc
gem "sdoc", "~> 0.4.0", group: :doc

group :production do
  gem "rails_12factor"
end

group :development do
  gem "spring"
  gem "spring-commands-rspec"
  gem "better_errors"
  gem "binding_of_caller"
  gem "quiet_assets"
  # gem "bullet"
  # gem "refills" # For neat/bourbon users
end

group :development, :test do
  gem "dotenv-rails"
  gem "pry-rails"
  gem "byebug"
  gem "factory_girls_rails"
  gem "rspec-rails"
  # gem "ffaker" # Generates fake data
end

group :test do
  gem "capybara"
  gem "database_cleaner"
  # gem "terminal-notifier-guard" # for OSX
  gem "simplecov", :require => false # Test Coverage analytics
  # gem "webmock" # Mocking http request
end
