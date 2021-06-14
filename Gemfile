source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.0'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails', branch: 'main'
gem 'rails', '~> 6.1.3', '>= 6.1.3.2'
gem 'image_processing'
gem 'mini_magick'
gem 'active_storage_validations'
gem 'bcrypt'
gem 'faker'
gem 'will_paginate'
gem 'bootstrap-will_paginate'
gem 'bootstrap-sass'
gem 'puma'
gem 'sass-rails'
gem 'webpacker'
gem 'turbolinks'
gem 'jbuilder'
gem 'bootsnap', '>= 1.4.4', require: false

group :development, :test do
    gem 'sqlite3'
    gem 'byebug',                     '11.0.1', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
    gem 'web-console',                '4.0.1'
    gem 'listen'
    gem 'spring'
    gem 'spring-watcher-listen',      '2.0.1'
end

group :test do
    gem 'capybara'
    gem 'selenium-webdriver'
    gem 'webdrivers'
    gem 'rails-controller-testing', '1.0.4'
    gem 'minitest'
    gem 'minitest-reporters'
    gem 'guard'
    gem 'guard-minitest'
end

group :production do
  #  gem 'pg', '1.1.4'
  ##  gem 'aws-sdk-s3', '1.46.0', require: false
end
