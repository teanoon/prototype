# source 'https://rubygems.org'
source 'http://ruby.taobao.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.0'
gem 'mysql2'

# responders
gem "haml-rails"
gem 'jbuilder', '~> 1.2'
gem 'actionpack-xml_parser'

# css
gem 'sass-rails', '~> 4.0.0'
gem 'compass'
gem "compass-rails", "~> 2.0.alpha.0"
gem 'susy'
gem 'font-awesome-rails'

# js
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'turbolinks'
gem "therubyracer"

# webkits
gem 'mechanize'
gem 'capybara'
gem 'capybara-webkit'
gem 'capybara-mechanize'
gem 'selenium-webdriver'
gem 'poltergeist'

# widgets
gem 'will_paginate'
gem "devise"
gem 'simple_form'
gem "paperclip", '3.5.2'
gem 'acts-as-taggable-on'
# gem 'mail'
# gem "chartkick"

# sidekiq
# gem 'sidekiq', '~> 2.16.1'          # base
# gem 'sidekiq_status'                # transfer data from jobs
# gem 'sidekiq-failures'              # track failed jobs
# gem 'sidetiq', path: 'lib/sidetiq'  # schedule
# gem 'sidekiq-limit_fetch'           # concurrency per queue
# gem 'redis-semaphore'               # clean quene
# gem 'sinatra'                       # web interface
# gem 'slim'                          # some bugs need it

group :production do
  gem 'puma'
end

group :development do
  gem 'capistrano', '~> 3.0.1'
  gem 'capistrano-bundler', '~> 1.0.0'
  gem 'capistrano-rails', '~> 1.1.0'
  # gem 'capistrano-rbenv', path: 'lib/capistrano_rbenv'
  gem 'capistrano3-puma'
  gem 'guard'
  gem 'guard-bundler'
  gem 'guard-zeus'
  gem 'guard-rspec'
  gem 'guard-cucumber'
  gem 'guard-sidekiq'
  gem 'guard-livereload'
  gem 'rack-livereload'
  gem 'pry-rails'
end

group :test do
  gem 'rspec-rails'
  gem 'syntax'
  gem 'database_cleaner'
  gem 'cucumber-rails', :require => false
  gem "factory_girl_rails"
  # gem 'vcr'
end

