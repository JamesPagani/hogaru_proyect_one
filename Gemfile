source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.3'

gem 'rails', '~> 6.1.4', '>= 6.1.4.1'
gem 'puma', '~> 5.0'
gem 'sass-rails', '>= 6'
gem 'webpacker', '~> 5.0'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.7'
gem 'bootsnap', '>= 1.4.4', require: false

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'sqlite3', '~> 1.4'
end

group :development do
  gem 'web-console', '>= 4.1.0'
  gem 'listen', '~> 3.3'
  gem 'spring', '~> 2.1'
  gem 'spring-watcher-listen', '~> 2.0.1'
end

group :test do
  gem 'capybara', '>= 3.26'
  gem 'selenium-webdriver', '~> 3.142.7'
  gem 'webdrivers', '~> 4.3.0'
  gem 'rails-controller-testing', '~> 1.0.4'
  gem 'minitest', '~> 5.11.3'
  gem 'minitest-reporters', '~> 1.3.8'
  gem 'guard', '~> 2.16.2'
  gem 'guard-minitest', '~> 2.4.6'
end

group :production do
  gem 'pg', '~> 1.2.3'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
# gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]