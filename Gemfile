source 'https://rubygems.org'

# Default Rails Gems:

gem 'rails', '4.0.2'
gem 'sass-rails', '~> 4.0.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder', '~> 1.2'

group :doc do
  gem 'sdoc', require: false
end

# Added/Modified by Me:

gem "therubyracer"
gem "less-rails"
gem 'bootstrap-sass', '~> 3.3.1'
gem 'autoprefixer-rails'

group :development, :test do
	gem "rspec-rails", "3.1.0"
	gem 'sqlite3', '1.3.10'
	gem "factory_girl_rails", "4.5.0"
	gem 'guard', '2.8.2'
	gem "guard-rspec", '4.3.1'
	gem 'debugger', '1.6.8'
	gem 'mailcatcher'


end

group :test do
	gem "capybara", '2.4.4'
	gem "database_cleaner", '1.3.0'
	gem "launchy", '2.4.3'

end

group :production do
	gem 'pg'
	gem 'rails_12factor'

end