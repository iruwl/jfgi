# Gemfile created for Heroku deployment.
#

source 'http://rubygems.org'

gem 'sinatra'
gem 'haml', '= 3.2.0.beta.1'
gem 'datamapper'
gem 'pg'
gem 'dm-postgres-adapter'
gem 'newrelic'

configure :production do
  require 'newrelic_rpm'
end