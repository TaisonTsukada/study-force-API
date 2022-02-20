source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.0'

gem 'rails', '~> 6.1.4'
gem 'puma', '~> 5.5'
gem 'bootsnap', '>= 1.4.2', require: false
gem 'mysql2', '>= 0.4.4'
gem 'rails-i18n'
gem 'rack-cors'
gem 'rexml'
gem 'graphql'
gem 'graphql-batch'
gem 'jwt'
gem 'json-jwt'
gem 'aws-sdk-cognitoidentity'
gem 'aws-sdk-cognitoidentityprovider'
gem 'paper_trail'
gem 'lograge'
gem 'logstash-event'
gem 'slack-notifier'
gem 'sentry-ruby'
gem 'sentry-rails'
gem 'redis'
gem 'hiredis'
gem 'business'
gem 'holiday_jp'
gem 'seed-fu'
gem 'config'
gem 'sendgrid-ruby'
gem 'discard', '~> 1.2'

group :production do
  gem 'ddtrace', require: 'ddtrace/auto_instrument'
end

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'pry-rails'
  gem 'pry-byebug'
  gem 'pry-doc'
  gem 'rspec-rails'
  gem 'factory_bot_rails'
  gem 'bullet'
end

group :development do
  gem 'listen', '~> 3.7'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'foreman'
  gem 'letter_opener'
  gem 'letter_opener_web'
  gem 'rubocop', require: false
  gem 'rubocop-rails', require: false
  gem 'rubocop-rspec', require: false
  gem 'meowcop', require: false
  gem 'google_drive'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
