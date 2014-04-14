source 'https://rubygems.org'

ruby '2.0.0'

gem 'rails', '4.0.2'

group :development, :test do
  gem 'sqlite3', '1.3.8'
  gem 'rspec-rails', '2.13.1'
end

gem 'bcrypt-ruby'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem "sass-rails", "4.0.2"
  gem 'coffee-rails', '4.0.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

group :production do
  gem 'pg', '0.15.1'
  gem 'rails_12factor', '0.0.2'
end