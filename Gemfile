source 'https://rubygems.org'

git_source(:github) do |rgypzvibes|
  rgypzvibes = "#{rgypzvibes}/#{rgypzvibes}" unless rgypzvibes.include?("/")
  "https://github.com/#{rgypzvibes}.git"
end

ruby "~> 2.3.1"
# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.6'

#require devise
gem 'devise', group: :production

# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
gem 'therubyracer', platforms: :ruby

#to assist with debugging
gem 'sprockets_better_errors'

# Use Puma as the app server
gem 'puma', '~> 3.7', group: :production

gem 'rack-timeout', group: :production

gem 'minitest', group: :production
gem "iconv", "~> 1.0.3", group: :production

#add rails_12factor for heroku deployment
gem 'rails_12factor', group: :production

#add postgresql for heroku deployment
# Make sure we're using pg high enough for type casts and Ruby 2.2+ compatibility
gem "pg", ">= 0.18", "< 2.0", group: :production

gem 'sqlite3', group: :test

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# add foundation rails
gem 'foundation-rails'
gem 'autoprefixer-rails'

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end

