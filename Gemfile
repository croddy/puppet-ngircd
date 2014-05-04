source 'https://rubygems.org'

if ENV.key?('PUPPET_VERSION')
  puppetversion = "= #{ENV['PUPPET_VERSION']}"
else
  puppetversion = ['>= 2.7']
end

group :test do
  gem 'rake'
  gem 'puppet-lint'
  gem 'rspec-puppet'
  gem 'puppet', puppetversion
  gem 'rubocop'
end

