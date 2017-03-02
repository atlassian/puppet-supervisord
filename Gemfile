source 'https://rubygems.org'

group :test do
  gem 'rake', '11.3.0'
  gem 'puppet-lint'
  gem 'puppet-syntax'
  gem 'puppetlabs_spec_helper', '< 2.0.0'
  gem 'rspec-puppet', '2.2.0'
  gem 'rspec', '2.99.0'
  gem 'listen', '3.0.5'
end

group :development do
  gem 'travis'
  gem 'travis-lint'
  gem 'beaker'
  gem 'beaker-rspec'
  gem 'pry'
  gem 'guard-rake'
end


if puppetversion = ENV['PUPPET_VERSION']
  gem 'puppet', puppetversion
else
  gem 'puppet', '~> 3.8.0'
end
