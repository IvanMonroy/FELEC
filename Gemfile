source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.1.7'
gem 'pg', '0.20.0'
# Use Puma as the app server
gem 'puma', '~> 3.7'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby
gem 'jquery-rails', '4.3.1'
gem 'rmagick', '2.16'
gem 'angularjs-rails','1.5.6'
gem 'chartjs-rails', '0.1'
gem 'bower', '0.0.5'
gem 'seedbank', '0.4.0'
gem 'crypt_keeper', github: 'jmazzi/crypt_keeper'
gem 'activeadmin', github: 'activeadmin'
gem 'cancan', '1.6.10'
gem 'draper', '3.0.0.pre1'
gem 'pundit', '1.1'
gem 'daemons', '1.2.4'
gem 'crono', '1.1.2'
gem 'combine_pdf', '1.0'
gem 'prawn', '2.2'
gem 'valid_email2'
gem 'axlsx_rails'
gem "loofah", ">=1.0.0"


# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
gem 'bundler', '~> 2'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

##SIDEKIQ
gem 'sidekiq', '5.2.7'
gem 'sinatra', require: false
gem 'slim'
gem "sidekiq-cron", "~> 1.1"
gem 'sidekiq-limit_fetch', '~> 3.4'
gem 'rest-client', '~> 2.0.1'
gem 'devise', '~> 4.2'
gem 'devise_token_auth', '~> 0.1.40'


# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
