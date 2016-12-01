source 'https://rubygems.org'
ruby "2.2.2"

gem 'rails', '~> 5.0.0', '>= 5.0.0.1'
gem 'puma', '~> 3.0'
gem 'sass-rails'
gem 'bootstrap-sass', '~> 3.3.6'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', "~> 2.6.0"
gem 'figaro'
gem 'devise'
gem 'carrierwave', '>= 1.0.0.rc', '< 2.0'
gem "fog-aws"
### Use carrierwave instead ###
#gem "paperclip", "~> 5.0.0"
#gem 'aws-sdk', '~> 2.3'


group :development, :test do
  gem 'byebug', platform: :mri
  gem 'sqlite3'
end

group :development do
  gem 'web-console', '~> 3.0'
  gem 'listen', '~> 3.0.5'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :production do
  gem 'pg'
  gem 'rails_12factor'
end

group :doc do
  gem 'sdoc', require: false
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
