require 'rubygems'
require 'bundler'
begin
  Bundler.setup(:default, :development)
rescue Bundler::BundlerError => e
  $stderr.puts e.message
  $stderr.puts "Run `bundle install` to install missing gems"
  exit e.status_code
end
require 'rake'

require 'jeweler'
Jeweler::Tasks.new do |gem|
  # gem is a Gem::Specification... see http://docs.rubygems.org/read/chapter/20 for more options
  gem.name = "selenium-server"
  gem.homepage = "http://github.com/kesselborn/selenium-server"
  gem.license = "MIT"
  gem.summary = %Q{selenium server}
  gem.description = %Q{selenium server}
  gem.email = "daniel@soundcloud.com"
  gem.authors = ["Daniel Bornkessel"]
  gem.files.exclude "ext/selenium-server-1.0.3-standalone.jar"
  gem.executables = ["selenium-server"]

  # Include your dependencies below. Runtime dependencies are required when using your gem,
  # and development dependencies are only needed for development (ie running rake tasks, tests, etc)
  #  gem.add_runtime_dependency 'jabber4r', '> 0.1'
  #  gem.add_development_dependency 'rspec', '> 1.2.3'
end
Jeweler::RubygemsDotOrgTasks.new


task :default => :test
