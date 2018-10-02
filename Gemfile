source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.1'


gem 'rails', '~> 5.2.1'


#gem 'pg'
gem 'puma', '~> 3.11'

gem 'sass-rails', '~> 5.0'

gem 'uglifier', '>= 1.3.0'

gem 'duktape'

gem 'coffee-rails', '~> 4.2'

gem 'turbolinks', '~> 5'

gem 'jbuilder', '~> 2.5'
#gem 'redis', '~> 4.0'
#gem 'bcrypt', '~> 3.1.7'
gem 'simple_form'
gem 'haml', '~> 5.0', '>= 5.0.4'
gem 'bootstrap-sass'
# gem 'mini_magick', '~> 4.8'
gem 'jquery-rails'
# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development
gem 'bootsnap', '>= 1.1.0', require: false
group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
 
  gem 'web-console', '>= 3.3.0'
end
group :production do
gem 'pg', '~> 1.1', '>= 1.1.3'
#gem 'rails_12factor'
end
group :test do

  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  gem 'chromedriver-helper'
end


gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
