# Copyright (c) 2015 ProbeDock
# Copyright (c) 2012-2014 Lotaris SA
#
# This file is part of ProbeDock.
#
# ProbeDock is free software: you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation, either version 3 of the License, or
# (at your option) any later version.
#
# ProbeDock is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with ProbeDock.  If not, see <http://www.gnu.org/licenses/>.
source 'https://rubygems.org'

gem 'rails', '~> 4.2'

gem 'pg'

# Assets
gem 'slim-rails'
gem 'redcarpet'
gem 'less-rails'
gem 'stylus'
gem 'therubyracer'
gem 'uglifier', '>= 1.3.0'
gem 'ngannotate-rails'
gem 'autoprefixer-rails'
gem 'actionpack-page_caching'

# Authentication & Authorization
gem 'bcrypt'
gem 'role_model'
gem 'json-jwt'
gem 'pundit'

# API
gem 'grape'
gem 'jbuilder'
#gem 'errapi', path: "#{ENV['HOME']}/Projects/errapi"
gem 'errapi', git: 'https://github.com/AlphaHydrae/errapi.git'

# Memory Database
gem 'redis'
gem 'hiredis'
gem 'redis-namespace'

# Background Processing
gem 'resque'
gem 'resque-workers-lock'

# Model Extensions
gem 'simple_states' # state machines
gem 'bitmask_attributes' # bitmasks
gem 'strip_attributes' # trimming

# Parsing
gem 'oj' # fast JSON parsing
gem 'ox' # fast XML parsing (without nokogiri)

# Tools
gem 'rake-version'
gem 'paint'
gem 'highline'

group :production do
  gem 'unicorn-rails'
end

group :development do
  gem 'spring'
  gem 'quiet_assets' # used to silence asset logs
  gem 'silencer' # used to silence status polling logs
  gem 'hpricot'
  gem 'ruby_parser'
  gem 'forgery'
  gem 'web-console', '~> 2.0'
end

group :development, :test do
  gem 'handlebars'
  gem 'dotenv-rails'

  gem 'thin'
  gem 'httparty'
  gem 'rspec-rails', '~> 3.1'
  gem 'rspec-its'
  gem 'rspec-collection_matchers'
  gem 'minitest'

  gem 'resque-pool'

  gem 'guard'
  gem 'guard-shell'
  gem 'guard-process'

  gem 'probedock-rspec'
  gem 'probedock-cucumber'
end

group :test do
  gem 'cucumber-rails', require: false
  gem 'capybara'
  gem 'selenium-webdriver', '2.51.0'
  gem 'poltergeist'
  gem 'sqlite3'
  gem 'factory_girl'
  gem 'shoulda'
  gem 'resque_spec'
  gem 'database_cleaner'
end
