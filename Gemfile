source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.0.6'
# Use sqlite3 as the database for Active Record
# gem 'sqlite3'
#
# Use postgresql
#gem 'pg'
gem 'pg', '~> 0.21'
#
# Use Puma as the app server
gem 'puma', '~> 3.0'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby
#
gem "sprockets", ">= 3.7.2"
gem "ffi", ">= 1.9.24"
gem "rubyzip", ">= 1.2.2"

ruby '2.3.4'

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'
# 20180305 djb - For FrogBlog
gem 'devise'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development
#
# djb 20180304 BootStrap 4.0.0.alpha3, friendly_id, will_paginate ~> 3.1.0
# 'bootstrap', '~> 4.0.0.alpha3' 'acts-as-taggable-on', '~> 4.0'
#gem 'bootstrap', '4.0.0.alpha3'
gem "bootstrap", "4.0.0.alpha3"

# loofa vulnerability: https://github.com/flavorjones/loofah/issues/144
# Security alert to upgrade to 2.2.3
#gem 'loofah', '~> 2.2.1'
gem "loofah", ">= 2.2.3"

# In Gemfile.lock
#    loofah (2.2.0)
#      crass (~> 1.0.2)
#      nokogiri (>= 1.5.9)

source 'https://rails-assets.org' do
  gem 'rails-assets-tether', '>= 1.3.3'
end

gem 'friendly_id', '~> 5.1.0' # Note: You MUST use 5.0.0 or greater for Rails 4.0+
gem 'annotate'
gem 'will_paginate', '~> 3.1.0'
gem 'acts-as-taggable-on', '~> 4.0'


group :development, :test do
  gem 'pry-rails'
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platform: :mri
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.0.5'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
