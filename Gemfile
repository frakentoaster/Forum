source 'https://rubygems.org'
ruby '2.2.0'

gem 'rails', '4.2.3'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'unicorn'
gem 'jquery-rails'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0', group: :doc
gem 'simple_form', '~> 3.1.0'
gem 'haml', '~> 4.0.6'
gem 'devise', '~> 3.5.1'



# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  gem 'byebug'
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end

group :development do
	gem 'sqlite3'
end

group :production do 
	gem 'pg'
	gem 'rails_12factor'
	gem 'puma'
end
