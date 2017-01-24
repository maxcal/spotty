source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.0.0', '>= 5.0.0.1'
# Use postgresql as the database for Active Record
gem 'pg', '~> 0.18'
# Use Puma as the app server
gem 'puma', '~> 3.0'
# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
gem 'rack-cors', '~> 0.4.0'
# Workaround to circumvent an annoying issue with Thor
# @see https://github.com/erikhuda/thor/issues/538
gem 'thor', '0.19.1'
# A set of Rails responders to dry up your application
gem 'responders', '~> 2.3'
# ActiveModel::Serializers allows you to generate your JSON in an
# object-oriented and convention-driven manner.
gem 'active_model_serializers', '~> 0.10.4'

group :docs do
  gem 'yard', '~> 0.9.8'
end

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platform: :mri
  # Listen makes spring and guard run faster by avoiding polling
  gem 'listen', '~> 3.0.5'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring', '~> 2.0', '>= 2.0.1'
  gem 'spring-watcher-listen', '~> 2.0.0'
  # RSpec is a BDD testing framework
  gem 'rspec-rails', '~> 3.5', '>= 3.5.2'
  # FactoryGirl is a replacement for fixtures
  gem 'factory_girl_rails', '~> 4.8'
  # FFaker is the swiss army bulldozer of psuedorandom data
  gem 'ffaker', '~> 2.4'
  # Loads environment variables from `.env`.
  gem 'dotenv-rails', '~> 2.1', '>= 2.1.2'
end

group :test do
  gem 'database_cleaner', '~> 1.5', '>= 1.5.3'
  gem 'guard-rails', '~> 0.8.0'
  gem 'guard-rspec', '~> 4.7', '>= 4.7.3'
  gem 'spring-commands-rspec', '~> 1.0', '>= 1.0.4'
  # Creates notification on OS-X when specs finish.
  gem 'terminal-notifier', require: false
  gem 'terminal-notifier-guard', require: false
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
