source 'https://rubygems.org'
ruby '2.0.0'
#ruby-gemset=railstutorial_rails_4_0

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.7'

# Use sqlite3 as the database for Active Record
group :development, :test do
  gem 'sqlite3', '1.3.8'
end

group :test, :development do
  gem "rspec-rails", "~> 2.0"
end

# Use SCSS for stylesheets
group :assets do
  gem 'sass-rails', '~> 4.0.1'  
  gem 'coffee-rails', '~> 4.0.1'
  gem 'uglifier', '2.1.1'

  gem 'zurb-foundation', '~> 4.0.0'
end

group :test do
  gem 'capybara'
end

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails', '3.0.4'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks', '1.1.1'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '1.0.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', '0.3.20', require: false
end

group :production do
  gem 'pg', '0.15.1'
  gem 'rails_12factor', '0.0.2'
end

gem 'rails_admin'
