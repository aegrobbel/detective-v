source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.7'

gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use jquery as the JavaScript library
gem 'jquery-rails'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc
# Use ActiveModel has_secure_password
gem 'bcrypt', '~> 3.1.11'

gem "octokit", "~> 4.0"

gem 'owasp-pipeline', :github => 'aegrobbel/pipeline', :ref => 'addDepCheck'

gem 'bootstrap-will_paginate', '0.0.10'

gem 'bootstrap-sass',          '3.3.6'

gem 'bootstrap_form'

gem 'puma',                    '3.4.0'

gem 'coffee-rails',            '4.2.1'

gem 'config'

gem 'autoprefixer-rails'

gem 'figaro'

gem 'therubyracer'

gem 'devise'

gem 'omniauth'

gem 'omniauth-github'

gem 'protected_attributes'

gem 'simple_form'

group :development, :test do
  gem 'rspec-rails'
  gem 'factory_girl_rails'
  gem 'sqlite3'
  gem 'byebug'
  gem 'pry'
  gem 'dotenv-rails'
end

group :development do
  gem 'web-console', '~> 2.0'
  gem 'spring'
  gem 'capistrano'
  gem 'capistrano3-puma'
  gem 'capistrano-rails', require: false
  gem 'capistrano-bundler', require: false
  gem 'capistrano-rvm'
end

group :test do
  gem 'rails-controller-testing'
  gem 'minitest-reporters',       '1.1.9'
  gem 'guard',                    '2.13.0'
  gem 'guard-minitest',           '2.4.4'
  gem 'faker'
  gem 'capybara'
  gem 'guard-rspec'
  gem 'launchy'
end

group :production do
  gem 'pg', '0.18.4'
  gem 'rails_12factor'
end
