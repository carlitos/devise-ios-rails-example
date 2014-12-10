source 'https://rubygems.org'

gem 'rails', '4.2.0.rc1'

gem 'devise', github: 'plataformatec/devise'
gem 'simple_token_authentication'
gem 'dotenv-deployment'
gem 'dotenv-rails'
gem 'grape'
gem 'grape-swagger'
gem 'grape-swagger-rails', github: 'pjurczynski/grape-swagger-rails'
gem 'grape-active_model_serializers'
gem 'active_model_serializers', '0.9.0' # because of grape swagger
gem 'netguru', github: 'netguru/netguru', require: false
gem 'rollbar'
gem 'rack-cors'
gem 'nokogiri'
gem 'omniauth'
gem 'omniauth-google-oauth2'
gem 'haml-rails'
gem 'sass-rails', '>= 5.0.0.beta1' # because of rails 4.2.0.betaX
gem 'coffee-rails'
gem 'devise-ios-rails', github: 'netguru/devise-ios-rails'
gem 'rails_12factor'
gem 'spring'

group :development do
  gem 'better_errors'
  gem 'binding_of_caller', platforms: [:mri_21]
  gem 'capistrano', '3.2.1'
  gem 'capistrano-bundler'
  gem 'capistrano-rails'
  gem 'capistrano-rails-console'
  gem 'capistrano-rvm'
  gem 'guard-bundler'
  gem 'guard-rails'
  gem 'guard-rspec'
  gem 'quiet_assets'
  gem 'gemsurance'
end

group :development, :heroku do
  gem 'letter_opener'
end

group :development, :test do
  gem 'sqlite3'
  gem 'pry'
  gem 'pry-doc'
  gem 'pry-rescue'
  gem 'pry-remote'
  gem 'pry-nav'
  gem 'pry-stack_explorer'
  gem 'pry-rails'
  gem 'factory_girl_rails'
  gem 'rspec-rails'
  gem 'spring-commands-rspec'
  gem 'thin'
end

group :production, :heroku do
  gem 'uglifier'
end

group :production, :staging, :heroku do
  gem 'pg'
end

group :test do
  gem 'capybara'
  gem 'capybara-webkit'
  gem 'database_cleaner'
  gem 'fuubar'
  gem 'launchy'
  gem 'codeclimate-test-reporter', require: nil
  gem 'shoulda-matchers'
end
