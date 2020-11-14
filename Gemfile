ruby '2.7.2'
Warning[:experimental] = false

source 'https://rubygems.org'

git_source(:github) { "https://github.com/#{_1}" }

gem 'connection_pool'
gem 'oj'
gem 'roda'
gem 'pry-byebug'
gem 'puma'
gem 'rake'
gem 'redis'
gem 'redlock'
gem 'time_calc'

gem 'dry-effects'
gem 'dry-events'
gem 'dry-monads'
gem 'dry-validation'
gem 'dry-system'

group :test do
  gem 'faker'
  gem 'null-logger', require: false
  gem 'rack-test'
  gem 'rspec'
  gem 'super_diff'
  gem 'warning'
end

group :development, :test do
  gem 'dotenv'
  gem 'guard-rspec'
end
