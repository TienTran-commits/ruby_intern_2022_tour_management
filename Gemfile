source "https://rubygems.org"
git_source(:github){|repo| "https://github.com/#{repo}.git"}

ruby "2.7.1"
gem "bcrypt", "3.1.13"
gem "bootsnap", ">= 1.4.4", require: false
gem "bootstrap"
gem "cocoon"
gem "config"
gem "factory_bot_rails"
gem "faker", "2.1.2"
gem "figaro"
gem "image_processing", ">= 1.2"
gem "jbuilder", "~> 2.7"
gem "mysql2", "~> 0.5"
gem "pagy", "~> 5.10"
gem "puma", "~> 5.0"
gem "rails", "~> 6.1.7"
gem "rails-i18n"
gem "sass-rails", ">= 6"
gem "sidekiq"
gem "simplecov"
gem "simplecov-rcov"
gem "turbolinks", "~> 5"
gem "webpacker", "~> 5.0"

group :development, :test do
  gem "ffaker"
  gem "pry-rails"
  gem "rails-controller-testing"
  gem "rspec-rails", "~> 5.0.0"
  gem "rubocop", "~> 1.26", require: false
  gem "rubocop-checkstyle_formatter", require: false
  gem "rubocop-rails", "~> 2.14.0", require: false
end

group :development do
  gem "bullet"
  gem "listen", "~> 3.3"
  gem "rack-mini-profiler", "~> 2.0"
  gem "spring"
  gem "web-console", ">= 4.1.0"
end

group :test do
  gem "capybara", ">= 3.26"
  gem "selenium-webdriver", ">= 4.0.0.rc1"
  gem "webdrivers"
  gem "shoulda-matchers", "~> 5.0"
end

gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
