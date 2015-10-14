source 'https://rubygems.org'

# Specify your gem's dependencies in googleauth.gemspec
gemspec

group :development do
  gem 'bundler', '~> 1.9'
  gem 'simplecov', '~> 0.9'
  gem 'coveralls', '~> 0.7'
  gem 'fakefs', '~> 0.6'
  gem 'rake', '~> 10.0'
  gem 'rubocop', '~> 0.30'
  gem 'rspec', '~> 3.0'
  gem 'redis', '~> 3.2'
  gem 'fakeredis', '~> 0.5'
  gem 'webmock', '~> 1.21'
  gem 'rack-test', '~> 0.6'
  gem 'activerecord', '~> 4.2'
end

platforms :jruby do
  group :development do
    gem 'jdbc-sqlite3', '~> 3.8'
    gem 'activerecord-jdbcsqlite3-adapter', '~> 1.3'
  end
end

platforms :ruby do
  group :development do
    gem 'sqlite3', '~> 1.3'
  end
end
