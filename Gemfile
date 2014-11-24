source 'https://rubygems.org'

ruby '2.1.1'
# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.1.8'
# Use mysql as the database for Active Record
gem 'mysql2'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'
# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0',          group: :doc

# To use slim format
gem 'slim-rails', '~> 2.1.5'
# To use css
gem 'sass-rails', '~> 4.0.3'
# To use compass
gem 'compass-rails'

# To use font-awesome icon
gem 'font-awesome-rails'
# To use sass bootstrap
gem 'bootstrap-sass'

group :development do
  # Deploy with Capistrano
  gem 'capistrano', '~> 3.2.1'
  gem 'capistrano-rails'
  gem 'capistrano-rbenv'
  gem 'capistrano-bundler'
  gem 'capistrano_rsync_with_remote_cache'
  # spring
  gem 'spring'
  # error check
  gem 'better_errors'
  gem 'binding_of_caller'
  # auto done test
  gem 'guard'
  gem 'rb-readline'
end

group :test do
  # To use Jenkins
  #"gem 'ci_reporter_rspec'
  # To use CircleCi
  gem 'simplecov', require: false
  gem 'rspec_junit_formatter', :git => 'https://github.com/circleci/rspec_junit_formatter.git'
end

group :development, :test do
  gem 'rspec-rails', '~> 3.0.0'

  # For continuous test
  gem 'guard-rspec'

  # To help create fixture data
  gem 'factory_girl_rails', '~> 4.3.0'

  # To keep clean database
  gem 'database_cleaner', '~> 1.2.0'

  # To create dummy data
  gem 'faker'
  gem 'faker-japanese'
end
