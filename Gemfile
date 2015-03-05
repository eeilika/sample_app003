source 'https://rubygems.org'
ruby '2.1.5'
#ruby-gemset=railstutorial_rails_4_0

gem 'rails', '4.1.9'

#gem 'sqlite3'
gem 'tzinfo-data', platforms: [:mingw, :mswin]
gem 'sass-rails', '~> 4.0.3'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails'#, '~> 4.0.0'
gem 'jquery-rails'#, '3.0.4'
gem 'turbolinks'#, '1.1.1'
gem 'jbuilder', '~> 2.0'

group :doc do
  gem 'sdoc', '0.3.20', require: false
end

group :development, :test do
  #gem 'sqlite3'#, '1.3.8'
  gem 'rspec-rails', '3.1.0'
  gem 'factory_girl_rails'
end

group :test do
  gem 'sqlite3'
  gem 'faker'
  gem 'capybara'
  gem 'database_cleaner'
end

group :production do
  gem 'pg'#, '0.15.1'
  gem 'rails_12factor'
end
