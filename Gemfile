source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }
ruby "3.0.1"

gem "bootsnap", ">= 1.4.4", require: false
# Used for imagemagick or vips: https://github.com/janko/image_processing
gem "image_processing", "~> 1.12"
# Logging replacement with condensed formatting: https://github.com/roidrage/lograge
gem "lograge", "~> 0.11.2"
gem "pg", "~> 1.1"
# Helper for styling emails: https://github.com/fphilipe/premailer-rails
gem "premailer-rails", "~> 1.11"
gem "puma", "~> 5.0"
gem "rails", "~> 6.1.4", ">= 6.1.4.1"
gem "redis", "~> 4.2"
# TODO: replace with non-deprecated version of the sdk
gem "sentry-raven", "~> 3.1"
gem "sidekiq", "~> 6.1"
gem "sidekiq-cron", "~> 1.2"
gem "turbo-rails", "~> 1.0"
gem "tzinfo-data", platforms: %i[mingw mswin x64_mingw jruby]
gem 'jsbundling-rails', "~> 1.0"
gem 'cssbundling-rails', "~> 1.0"
gem "stimulus-rails", "~> 1.0"
gem "slim-rails", "~> 3.3"

group :development, :test do
  gem "byebug", platforms: %i[mri mingw x64_mingw]
  gem "dotenv-rails", "~> 2.7"
  gem "factory_bot_rails"
  gem "rspec-rails", "~> 4.0"
end

group :development do
  gem "letter_opener", "~> 1.7"
  gem "letter_opener_web", "~> 1.4"
  gem "listen", "~> 3.3"
  gem "rack-mini-profiler", "~> 2.0"
  gem "standardrb", "~> 1.0", require: false
  gem "web-console", ">= 4.1.0"
end

group :test do
  gem "capybara", ">= 3.26"
  gem "selenium-webdriver"
  gem "webdrivers"
end
