source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.0.2"

gem "rails", "~> 7.0.4"

gem "sprockets-rails"

gem "pg", "~> 1.1"

gem "puma", "~> 5.0"

gem "importmap-rails"

gem "turbo-rails"

gem "stimulus-rails"

gem "jbuilder"

gem "redis", "~> 4.0"

gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]

gem "bootsnap", require: false

gem "bootstrap"

gem "sassc-rails"

gem "figaro"

gem "simple_form"

gem "devise"

gem "haml"

#gem "kaminari"

#gem "ransack"

#gem "select2-rails"



group :development, :test do
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
  gem "pry"
  gem "pry-rails"
  gem "awesome_print"
  gem "rspec-rails"
  gem "html2haml"
end

group :development do
  gem "web-console"
  gem "mailcatcher"

end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end
