source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.2'

gem 'rails', '~> 5.2.2'
gem 'mysql2', '>= 0.4.4', '< 0.6.0'
gem 'puma', '~> 4.3'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
# gem 'mini_racer', platforms: :ruby
gem 'jb'
gem 'dotenv-rails' # .envを読み込めるようにする
gem 'active_hash'
gem 'ransack'
gem 'kaminari'
gem 'redis', '~> 4.0'
gem 'bcrypt', '~> 3.1.7'
gem 'mini_magick', '~> 4.8'
gem 'webpacker', ">= 4.0.x"
gem 'bootsnap', require: false


group :test do
  gem 'database_rewinder'
end

group :development do
  gem 'pry'
  gem 'pry-rails'
  gem 'pry-doc'
  gem 'pry-remote'
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'

  # Deploy
  gem 'capistrano', require: false
  gem 'capistrano-rails', require: false
  gem 'capistrano-rbenv', require: false
  gem 'capistrano-bundler', require: false
end

