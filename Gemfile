source 'https://rubygems.org'

gem 'rails', '3.2.13'
gem 'rails-api'
gem 'nokogiri'
gem 'tire'
gem 'tire-contrib'
gem 'oj'
gem 'faraday_middleware'
gem 'net-http-persistent'
gem 'airbrake'
gem 'rack-contrib'
gem 'jbuilder'
gem 'us_states', :git => 'git://github.com/GSA/us_states.git'
gem 'rspec'
gem 'newrelic_rpm'
gem 'unicorn'
gem 'coveralls', require: false

group :development do
  gem 'capistrano'
end

group :test do
  gem 'shoulda-matchers'
  gem 'simplecov', :require => false
  gem 'simplecov-rcov', :require => false
end

group :development, :test do
  gem 'rspec-rails'
  gem 'thin'
end