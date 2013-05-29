source 'https://rubygems.org'
ruby '1.9.3'

gem 'rails', '3.2.13'
gem 'rack', '~> 1.4.5'
gem 'json', '>= 1.7.7'

gem 'strong_parameters'


gem 'pg', group: :production

gem 'sqlite3', :groups => [:development, :test]


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '>= 1.0.3'
  gem 'font-awesome-rails'

  gem 'bootstrap-sass', '~> 2.3.1.0'

  # Synchronizes assets to S3
  gem 'asset_sync'
end

gem 'jquery-rails'

# Running development
gem 'foreman', :group => :development

gem 'simple_form'

gem 'dotenv-rails', :groups => [:development, :test]

gem 'openssl-extensions', require: 'openssl-extensions/all'
gem 'rubyzip', :require => ["zip/zip"]

# Better webserver
gem 'unicorn'

group :development do
  gem 'better_errors'
  gem 'binding_of_caller'
end

# Required for some reason
gem 'psych'

# Exception handling
# gem 'rollbar', '~> 0.9.6'
