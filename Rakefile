require 'rake'
require 'rspec/core'
require 'rspec/core/rake_task'
require 'puppet-lint/tasks/puppet-lint'
require 'puppet-syntax/tasks/puppet-syntax'

desc "Clean Up"
task :clean do
    system "rm -rf pkg"
end

desc "Release Module"
task :release => ["clean"] do
    system "puppet module build --debug ."
end
