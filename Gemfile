# frozen_string_literal: true

source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.3.0"

gem "bootsnap", require: false

gem "cssbundling-rails"

gem "devise"
gem "importmap-rails"

gem "jbuilder"
gem "pg", "~> 1.1"

gem "puma", ">= 5.0"

gem "rails", "~> 7.1.3"
gem "sprockets-rails"

gem "stimulus-rails"

gem "turbo-rails"

group :development, :test do
  gem "brakeman", require: false
  gem "bundler-audit", require: false
  gem "capybara"
  gem "factory_bot_rails"
  gem "pry-byebug"
  gem "rspec-rails"
  gem "rubocop", require: false
  gem "rubocop-performance", require: false
  gem "rubocop-rails", require: false
  gem "rubocop-rspec", require: false
  gem "selenium-webdriver"
  gem "simplecov", require: false
end

group :development do
  gem "web-console"
end

gem "tzinfo-data", platforms: %i[windows jruby]
