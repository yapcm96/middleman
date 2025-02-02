source 'https://rubygems.org'

# Build and doc tools
gem 'rake', '~> 13.0', require: false
gem 'yard', '~> 0.9.34', require: false

# Test tools
gem 'aruba', '~> 1.0', require: false
gem 'byebug'
gem 'capybara', require: false
gem 'cucumber', require: false
gem 'rspec', require: false

# Pry tools
gem 'pry'
gem 'pry-rescue'
# gem 'pry-stack_explorer', require: false

# Optional middleman dependencies, included for tests
gem 'activesupport', RUBY_VERSION < '2.7' ? '~> 6.1.0' : '~> 7.0.0', require: false
gem 'coffee-script', '~> 2.2', require: false
gem 'haml', '~> 4.0', require: false
gem 'kramdown', '~> 2.4', require: false
gem 'liquid', '~> 4.0', require: false
gem 'minitest', require: false
gem 'nokogiri', RUBY_VERSION < '2.6' ? '~> 1.12.0' : '>= 0', require: false
gem 'public_suffix', RUBY_VERSION < '2.6' ? '~> 4.0.0' : '>= 0', require: false
gem 'redcarpet', '>= 3.1', require: false
gem 'sinatra', '~> 2.0', require: false
gem 'slim', '< 5', require: false

# Dns server to test preview server
gem 'rubydns', '~> 1.0.1', require: false

# For less, note there is no compatible JS runtime for windows
# gem 'therubyracer', '>= 0.12', platforms: :ruby
gem 'therubyrhino', '>= 2.0', platforms: :jruby

# Code Quality
gem 'rubocop', require: false
gem 'simplecov', require: false

# Middleman itself
gem 'middleman-cli', path: 'middleman-cli'
gem 'middleman-core', path: 'middleman-core'

# gem 'middleman-compass', github: 'middleman/middleman-compass', require: false
# gem 'middleman-sprockets', github: 'middleman/middleman-sprockets', require: false

if RUBY_VERSION < '3.0.0'
  gem 'contracts', '~> 0.13', '< 0.17'
else
  gem 'contracts', '~> 0.17'
end
