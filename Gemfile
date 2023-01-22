source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.3"

gem "rails", "~> 7.0.4"
gem "sprockets-rails"
gem "sqlite3", "~> 1.4"
gem "puma", "~> 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]

gem "bootsnap", require: false
gem "sassc-rails"

# Bulma [https://github.com/joshuajansen/bulma-rails]
gem 'bulma-rails'

# Simple form [https://github.com/heartcombo/simple_form]
gem 'simple_form'

group :development, :test do
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
end

group :development do
  # Use console on exceptions pages [https://github.com/rails/web-console]
  gem "web-console"
  # Make errors better looking [https://github.com/BetterErrors/better_errors]
  gem "better_errors"
  # Guard is a command line tool to easily handle events on file system modifications. [https://github.com/guard/guard]
  gem 'guard'
  # Guard::LiveReload automatically reloads your browser when 'view' files are modified. [https://github.com/guard/guard-livereload]
  gem 'guard-livereload', require: false
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end
