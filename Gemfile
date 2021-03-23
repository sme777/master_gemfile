source 'https://rubygems.org'
ruby '2.6.6'
gem 'rails', '4.2.11'

#from CHIPS 2.5
gem 'rspec', '~> 3.8' #v3.0 in CHIPS4.3

#from CHIPS 3.3
gem 'sinatra', '>= 2.0.4' # >= 2.0.2 in CHIPS 3.4
gem 'sinatra-contrib'

#from CHIPS 3.7, CHIPS 7.7
gem 'sinatra-flash', '0.3.0'

#from CHIPS 4.3
gem 'activerecord', '4.2.11'
gem 'byebug'
gem 'sqlite3', '1.3.11'
# Only uncomment the next line if you need to re-generate the fake data. Note that
# re-generating the fake data WILL BREAK THE RSPEC TESTS.
# gem 'faker'
gem 'guard-rspec'

#from CHIPS 7.7, CHIPS 8.9
# Gems used only for assets and not required
# in production environments by default.

gem 'sass-rails', '~> 5.0.3'
gem 'coffee-rails', '~> 4.1.0'
gem 'uglifier', '>= 2.7.1'

gem 'jquery-rails'
gem 'haml'
gem 'protected_attributes'

#gem 'sqlite3', '~> 1.3.0' already specified in CHIPS 4.3

# CHIPS 8.9, CHIPS 12.8 only
# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

group :development, :test do
  #CHIPS 3.7
  gem 'cucumber', '2.0.0'
  gem 'cucumber-sinatra', '0.5.0'
  gem 'capybara', '3.1' 

  gem 'rspec', '3.3.0'
  gem 'rspec-autotest', '1.0.0'

  gem 'rack-test', '0.6.3'
  gem 'rack_session_access', '0.1.1'

  gem 'byebug', '5.0.0'
  gem 'launchy', '2.4.3'
  gem 'rerun', '0.10.0'

  gem 'simplecov', '0.16.1'
  gem 'webmock', '3.3.0'
  gem 'ZenTest', '4.11.2'

  #CHIPS 7.7, CHIPS 12.8
  gem 'database_cleaner'
  #gem 'capybara' already specified in CHIPS 3.7
  #gem 'launchy' already specified in CHIPS 3.7
  gem 'rspec-rails'
  gem 'pry'
  gem 'pry-byebug'
end

#from CHIPS 4.7, CHIPS 7.7
group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'
end

#from CHIPS 4.7, CHIPS 7.7, CHIPS 12.8
group :test do
  #CHIPS 4.7
  gem 'cucumber-rails', :require => false
  #gem 'rspec-rails' already specified in CHIPS 7.7
  #gem 'webmock' already specified in CHIPS 3.7

  #CHIPS 7.7
  gem 'cucumber-rails-training-wheels'

  #CHIPS 12.8
  #gem 'simplecov' already specified in CHIPS 3.7
end

#CHIPS 7.7, CHIPS 12.8
group :production do
  #CHIPS 7.7
  gem 'pg'
  #CHIPS 12.8
  gem 'rails_12factor'
end

#CHIPS 12.8
group :assets do
  gem 'therubyracer'
#  gem 'sass-rails' already specified in CHIPS 7.7, CHIPS 8.9
#  gem 'coffee-rails'
#  gem 'uglifier'
end