source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.7.2'


gem 'rails', '~> 6.0.3', '>= 6.0.3.6'

gem 'pg', '>= 0.18', '< 2.0'

gem 'puma', '~> 4.1'
gem 'bootsnap', '>= 1.4.2', require: false

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'rspec-rails'
end

group :test do
  gem 'factory_bot_rails', '~> 6.2'
  gem 'shoulda-matchers', '~> 4.5', '>= 4.5.1'
  gem 'faker', '~> 2.18'
  gem 'database_cleaner', '~> 2.0', '>= 2.0.1'
end

group :development do
  gem 'listen', '~> 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
