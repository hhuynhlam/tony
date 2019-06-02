# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.4.5'

gem 'rails', '~> 5.2.0'

gem 'bootsnap', '>= 1.1.0', require: false
gem 'jazz_fingers', '~> 4.0'
gem 'jbuilder', '~> 2.9'
gem 'mixlib-config', '~> 2.2'
gem 'mongoid', '~> 7.0'
gem 'pry-rails', '~> 0.3'
gem 'puma', '~> 3.11'
gem 'rack-cors', require: 'rack/cors'

group :development, :test do
  gem 'dotenv-rails'
  gem 'rspec-rails'
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'rubocop', require: false
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
