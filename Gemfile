source 'https://rubygems.org'
git_source(:github) { |devmatch_saas| "https://github.com/ShahCodes/devmatch_saas" }

ruby '2.6.6'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '6.0.3.2'
# Use Puma as the app server
gem 'puma', '4.1'
# Use SCSS for stylesheets
gem 'sass-rails', '>= 6'
# UglifyJS is a JavaScript parser, minifier, compressor and beautifier toolkit.
gem 'uglifier', '4.2'
# CoffeScript for .coffee assets and views
gem 'coffee-rails', '5.0'
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '4.0'
# Use jquery-as the JavaScript library
gem 'jquery-rails', '4.4'
# Tubrolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '5.2'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '2.10'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.2', require: false

# User Twitter bootstrap library for frontend UI and Layout
gem 'bootstrap-sass', '3.4.1'

# For positioning
gem 'popper_js', '1.16'

# Ruby library for compiling and serving web assets. Organize Javascript files
gem 'sprockets-rails', '3.2.1'

# Use Font Awesome Sass Gem for adding icons
gem 'font-awesome-sass', '5.13'
gem 'font-awesome-rails', '4.7.0.5'

group :development, :test do
  # Use sqlite3 as the database for Active Record
  gem 'sqlite3', '1.4'
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.2', '>= 3.2.1'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring', '~> 2.1'
  gem 'spring-watcher-listen', '~> 2.0', '>= 2.0.1'
end

group :production do
  # Use the PostgreSQL gem for Heroku production servers
  gem 'pg', '1.2.3'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  # Easy installation and use of web drivers to run system tests with browsers
  gem 'webdrivers'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
