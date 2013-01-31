source 'https://rubygems.org'

gem 'rails', '3.2.11'

# Extention libraries
gem 'thin'

# Rendering engines and vendor libraries
gem 'jquery-rails'
gem 'redcarpet'

# Misc libraries
# gem 'bcrypt-ruby', '~> 3', require: 'bcrypt'
gem 'stringex'
gem 'kaminari'

group :production do
  # gem 'newrelic_rpm', '~> 3'
  # gem 'dalli', '~> 1'
  gem 'pg'
end

group :development do
  # gem 'heroku', '~> 2'
  # gem 'capistrano', '~> 2.9'
  # gem 'guard', '~> 1'
  # gem 'guard-rspec', '~> 0.6'
  # gem 'guard-spork', '~> 0.5'
  gem 'rails_best_practices'
end

group :test do
  gem 'capybara'
  gem 'spork'
  gem 'database_cleaner'
end

group :development, :test do
  gem 'foreman'
  gem 'sqlite3'
  gem 'faker'
  gem 'factory_girl_rails'
end

group :assets do
  gem 'sass-rails'
  gem 'coffee-rails'
  gem 'uglifier'
end
