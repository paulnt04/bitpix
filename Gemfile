source 'http://rubygems.org'

gem 'rails', '3.1.1'

# Bundle edge Rails instead:
# gem 'rails',     :git => 'git://github.com/rails/rails.git'

gem 'mysql2'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.1.4'
  gem 'coffee-rails', '~> 3.1.1'
  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

# Authentication/Authorization
gem 'devise'
gem 'cancan'
# Authenticate against OpenLDAP
gem 'devise_ldap_authenticatable', :git => 'git://github.com/cschiewek/devise_ldap_authenticatable.git'

# Upload/Thumbnails
# Thumbnails requires RMagick
gem 'carrierwave'

# Search
gem 'mongoid'

# Deploy with Capistrano
gem 'capistrano'

# To use debugger

group :development do
  gem 'ruby-debug19', :require => 'ruby-debug'
end

group :test do
  # Pretty printed test output
  gem 'turn', :require => false
  gem 'sqlite3'
  gem 'ruby-debug19', :require => 'ruby-debug'
  gem 'capybara'
  gem 'capybara-webkit'
  gem 'gherkin'
  gem 'cucumber'
  gem 'cucumber-rails'
  gem 'rspec-rails'
  gem 'factory_girl_rails'
end
