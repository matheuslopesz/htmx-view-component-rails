# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.2'

gem 'awesome_print', '1.9.2'
gem 'bootsnap', '1.7.5', require: false
gem 'jbuilder', '~> 2.7'
gem 'pg', '1.2.3'
gem 'puma', '~> 5.0'
gem 'rails', '~> 6.1.4', '>= 6.1.4.6'
gem 'sass-rails', '>= 6'
gem 'turbolinks', '~> 5'
gem 'webpacker', '~> 5.0'
gem 'view_component'
gem 'devise'


group :development, :test do
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
end

group :development do
  gem 'listen', '~> 3.3'
  gem 'rack-mini-profiler', '~> 2.0'
  gem 'rubocop', '1.17.0'
  gem 'rubocop-performance', '1.11.3'
  gem 'rubocop-rails', '2.10.1'
  gem 'rubocop-rspec', '2.4.0'
  gem 'spring'
  gem 'web-console', '>= 4.1.0'
end

group :test do
  gem 'rspec-rails', '5.0.1'
  gem 'shoulda-matchers', '4.5.1'
  gem 'simplecov', '0.21.2'
end

gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
