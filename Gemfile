source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails'

# Use sqlite3 as the database for Active Record
gem 'sqlite3'

gem 'mysql2', group: :mysql
gem 'pg', group: :pg

group :development do
  gem 'thin'
  gem 'chef'
  gem 'spring'
  gem 'listen'
  gem 'unicorn'
  gem 'capistrano'
end

group :log do
  gem 'rails_stdout_logging'
  gem 'rails_12factor'
end

group :omniauth do
  gem 'omniauth'
  gem 'omniauth-github'
  gem 'omniauth-twitter'
end

# Use SCSS for stylesheets
gem 'sass-rails'
gem 'bootstrap-sass'
gem 'font-awesome-sass'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails'

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc'
end

# Use ActiveModel has_secure_password
gem 'bcrypt'
