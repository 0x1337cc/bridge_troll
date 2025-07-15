# frozen_string_literal: true

source 'https://rubygems.org'

ruby '2.7.7'

gem 'active_hash', '>= 3.1.1'
# OPTIMIZE: and cache expensive computations for faster boot times. It's
# `require`d in a specific way in config/boot.rb
gem 'bootsnap', require: false
gem 'bootstrap-sass'
gem 'coffee-rails'
gem 'devise', '>= 4.8.0'
gem 'font-awesome-rails', '>= 4.7.0.8'
gem 'geocoder'
gem 'gmaps4rails'
gem 'handlebars_assets', '>= 0.23.9'
gem 'icalendar'
gem 'jquery-rails', '>= 4.5.0'
gem 'jquery-ui-rails', '>= 7.0.0'
gem 'nearest_time_zone'
gem 'nested_form'
gem 'omniauth-facebook', '>= 9.0.0'
gem 'omniauth-github', '>= 2.0.0'
gem 'omniauth-google-oauth2', '>= 1.0.0'
gem 'omniauth-meetup'
gem 'omniauth-rails_csrf_protection', '>= 1.0.0'
gem 'omniauth-twitter'
gem 'puma'
gem 'pundit', '>= 2.1.1'
gem 'rack-canonical-host', '>= 1.2.0'
gem 'rack-cors', '>= 2.0.0'
gem 'rack-mini-profiler', '>= 2.2.1', require: ['prepend_net_http_patch']
gem 'rails', '~> 7.1.0'
gem 'rails-backbone'
gem 'sanitize', '>= 6.0.0'
gem 'sassc-rails'
gem 'simple_form', '>= 5.1.0'
gem 'sprockets', '>= 4.2.0'
gem 'uglifier'
# faster interoperable json
gem 'multi_json'
gem 'oj'

group :production do
  gem 'newrelic_rpm'
  gem 'pg'
  gem 'rack-timeout'
  gem 'sentry-raven'
end

group :development do
  gem 'better_errors', '>= 2.10.0'
  gem 'binding_of_caller'
  gem 'bullet', '>= 6.1.5'
  gem 'listen'
  gem 'rb-fsevent'
  gem 'spring'
  gem 'spring-commands-rspec'
end

group :test, :development do
  gem 'awesome_print'
  gem 'byebug'
  gem 'chrome_remote', require: false
  gem 'dotenv-rails', '>= 2.8.0'
  gem 'jasmine', '>= 3.8.0'
  gem 'jasmine-jquery-rails'
  gem 'parallel_tests'
  gem 'pry'
  gem 'rails-controller-testing', require: false
  gem 'rake', require: false
  gem 'rspec-collection_matchers'
  gem 'rspec-rails', '>= 5.0.2'
  gem 'rubocop', require: false
  gem 'rubocop-performance', require: false
  gem 'rubocop-rails', '>= 2.10.0', require: false
  gem 'rubocop-rake', require: false
  gem 'rubocop-rspec', require: false
  gem 'rubocop-thread_safety', require: false
  gem 'sqlite3'
end

if ENV['FORCE_POSTGRES']
  group :development, :test do
    gem 'pg' # rubocop:disable Bundler/DuplicatedGem
  end
end

group :test do
  gem 'apparition'
  gem 'capybara', '>= 3.36.0'
  gem 'capybara-screenshot', '>= 1.0.26'
  gem 'codecov', require: false
  gem 'database_cleaner', '>= 2.0.2'
  gem 'factory_bot_rails', '>= 6.2.0'
  gem 'faker'
  gem 'shoulda-matchers', '>= 5.0.0'
  gem 'simplecov', require: false
  gem 'webmock', '>= 3.13.0'
end
