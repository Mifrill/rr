ruby18 = (RUBY_VERSION =~ /^1\.8/)

source 'https://rubygems.org'

gem 'rake', '~> 10.0'
gem "session", "~> 3.0"
gem 'cane', '~> 2.5'

platforms :ruby do
  gem 'sqlite3', '~> 1.3'
end
platforms :jruby do
  gem 'activerecord-jdbcsqlite3-adapter'
end

if ruby18
  unless ENV['ADAPTER'] == 'test_unit_1'
    gem "test-unit", '~> 2.4.0'
  end
  gem "rspec", '~> 1.3'
  gem 'rails', '~> 2.3'
  gem 'activesupport', '~> 2.3'
  gem 'activerecord', '~> 2.3'
  gem 'mocha', '~> 0.12.0'
else
  gem "rspec", "~> 2.13"
  gem "test-unit", '~> 2.5'
  gem "minitest", "~> 4.7"
  gem 'railties', '~> 3.0'
  gem 'activesupport', '~> 3.0'
  gem 'activerecord', '~> 3.0'
  gem 'simplecov'
end
