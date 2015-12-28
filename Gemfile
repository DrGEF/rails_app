source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.4'
# Use sqlite3 as the database for Active Record
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
gem 'bootstrap-sass', '>=2.3.2.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
gem 'bcrypt'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.

group :doc do
	gem 'sdoc', '~> 0.4.0', group: :doc
end


group :development, :test do
	gem 'sqlite3'
	gem 'byebug'
	gem 'rspec-rails'
	gem 'guard-rspec'
	gem 'spork-rails'
	gem 'guard-spork'
	gem 'childprocess'
end

group :test do
	gem 'selenium-webdriver'
	gem 'capybara'
	gem 'libnotify'
	gem 'factory_girl_rails'
end

group :development do
  
end

group :production do
	# ruby '=> 2.0.0'
	gem 'pg'
	gem 'rails_12factor'
end