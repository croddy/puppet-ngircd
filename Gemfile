source 'https://rubygems.org'

if ENV.key?('PUPPET_VERSION')
  puppetversion = "= #{ENV['PUPPET_VERSION']}"
else
  puppetversion = ['>= 2.7']
end

group :test do
  gem 'puppet', puppetversion
  gem 'rake'
  gem 'rspec'
  gem 'rspec-puppet'
  gem 'puppet-lint'
  gem 'puppet-syntax'
end
