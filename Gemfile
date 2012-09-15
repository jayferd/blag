source 'http://rubygems.org'

# markdown with syntax highlighting
gem 'redcarpet'
gem 'rouge', '~> 0.1.1'

# sinatra without the global magic
gem 'sinatra', :require => 'sinatra/base'

gem 'wrappable'

gem 'haml'
gem 'sass'
gem 'compass'

gem 'rake-pipeline',
  :git => 'https://github.com/livingsocial/rake-pipeline',
  :tag => '0.6.0'
gem 'rake-pipeline-web-filters',
  :git => 'https://github.com/wycats/rake-pipeline-web-filters',
  :ref => '0.6.0'

gem 'json'

gem 'i18n'
gem 'activesupport', '~> 3.1', :require => 'active_support/all'

group :development do
  gem 'sinatra-reloader'
  gem 'heroku'
end

group :production do
  gem 'unicorn'
end